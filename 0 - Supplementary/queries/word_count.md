```dataviewjs

// Section titles to search for in each note
const sectionTitles = ["To Do"];

// Regular expression pattern for file names in the format YYYY-MM-DD
const fileNamePattern = /^\d{4}\d{2}\d{2}$/;

// Chart labels and styles
const chartLabel = 'Word Count';
const avgLineColor = 'rgba(255, 165, 0, 0.8)'; // Orange color for the average line

// Load Chart.js for graph rendering
const chartScript = document.createElement("script");
chartScript.src = "https://cdn.jsdelivr.net/npm/chart.js";
document.head.appendChild(chartScript);

chartScript.onload = async () => {
    // Get all notes that match the date format (YYYY-MM-DD)
    let journals = dv.pages().filter(p => fileNamePattern.test(p.file.name)).sort(p => p.file.mtime, 'desc');
    
    // Store word counts for each month (YYYY-MM)
    let wordCountsByMonth = new Map();

    // Loop through each journal, load its content, and extract word count under specific sections
    for (let journal of journals) {
        let content = await dv.io.load(journal.file.path);
        let sectionContent = getSectionContent(content, sectionTitles); // Extract relevant section content
        let wordCount = sectionContent ? sectionContent.split(/\s+/).length : 0; // Count words in the section
        let monthKey = journal.file.name.slice(0, 7); // Extract the month (YYYY-MM) from the file name

        // Accumulate word count for the month
        wordCountsByMonth.set(monthKey, (wordCountsByMonth.get(monthKey) || 0) + wordCount);
    }

    // Calculate the full range of months, including months with no data
    let currentMonth = new Date();
    let startDate = new Date(journals[journals.length - 1].file.name.slice(0, 7) + '-01');
    let endDate = new Date(currentMonth.getFullYear(), currentMonth.getMonth() + 1, 1); // Set endDate to the first day of the next month

    let allMonths = getMonthsInRange(startDate, endDate); // Get all months between the first and current month

    // Map word counts to each month in the full range
    let wordCounts = allMonths.map(month => wordCountsByMonth.get(month) || 0);

    // Filter out months with no word count to calculate average (ignore months with zero data)
    let validWordCounts = wordCounts.filter(count => count > 0);
    let averageWordCount = validWordCounts.reduce((a, b) => a + b, 0) / validWordCounts.length;

    // Only create the chart if there is valid data to display
    if (allMonths.length > 0 && wordCounts.length > 0) {
        let canvas = document.createElement("canvas");
        canvas.id = "myChart"; // Create a canvas element to hold the chart
        dv.container.appendChild(canvas); // Append the canvas to the current note

        // Create a gradient for the word count line (from red for highs, yellow for average, to blue for lows)
        let ctx = canvas.getContext('2d');
        let gradient = ctx.createLinearGradient(0, 0, 0, canvas.height);
        gradient.addColorStop(0, 'rgba(255, 0, 0, 0.6)');     // Red for highs
        gradient.addColorStop(0.4, 'rgba(255, 205, 86, 0.7)'); // Yellow for near average
        gradient.addColorStop(1, 'rgba(54, 162, 235, 0.4)');   // Blue for lows

        // Create the data structure for the chart
        const chartData = {
            labels: allMonths, // X-axis labels (months)
            datasets: [{
                label: chartLabel, // Word count label
                data: wordCounts,  // Word count data
                backgroundColor: gradient, // Gradient fill for the word count line
                borderColor: 'rgba(0, 0, 0, 0.1)', // Light border color
                fill: true, // Fill under the line
                borderWidth: 1, // Width of the line
                pointBackgroundColor: 'white', // White tips for points on the line
                pointBorderColor: 'black', // Black borders for the points
                pointBorderWidth: 1, // Point border width
                pointRadius: 4, // Size of the points
                pointHoverRadius: 6 // Size of points on hover
            }, {
                label: `Average Word Count (${Math.round(averageWordCount)})`, // Average line label
                data: Array(allMonths.length).fill(averageWordCount), // Average data across all months
                borderColor: avgLineColor, // Color of the average line
                fill: false, // Do not fill under the average line
                borderWidth: 2, // Line width for the average line
                pointRadius: 0, // No points for the average line
                type: 'line', // Line type
                borderDash: [10, 5],  // Dashed line for the average line
                tooltip: { // Tooltip callback for the average line
                    callbacks: {
                        label: function() {
                            return `Average Word Count: ${Math.round(averageWordCount)}`;
                        }
                    }
                }
            }]
        };

        // Render the chart with Chart.js
        new Chart(canvas, {
            type: 'line', // Type of chart (line chart)
            data: chartData, // Data for the chart
            options: {
                scales: {
                    x: { type: 'category' }, // Treat X-axis as categories (months)
                    y: { beginAtZero: true } // Start Y-axis from zero
                },
                plugins: {
                    tooltip: {
                        mode: 'nearest', // Show nearest tooltip on hover
                        intersect: false // Show tooltip even if not intersecting a point
                    }
                }
            }
        });
    } else {
        dv.paragraph("No valid data found to display the chart."); // Show message if no data exists
    }
};

// Helper function to extract content under the specified section headings
function getSectionContent(content, sectionHeadings) {
    for (let heading of sectionHeadings) {
        let regex = new RegExp(`${heading}[\\s\\S]*?(?=#|$)`, 'g'); // Regex to capture content under each heading
        let match = content.match(regex);
        if (match) {
            return match[0].replace(heading, '').trim(); // Return the content under the heading
        }
    }
    return ''; // Return empty if no matching heading found
}

// Helper function to get all months between startDate and endDate (inclusive)
function getMonthsInRange(startDate, endDate) {
    let date = new Date(startDate);
    let months = [];

    while (date <= endDate) {
        months.push(date.toISOString().slice(0, 7)); // Add each month in YYYY-MM format
        date.setMonth(date.getMonth() + 1); // Move to the next month
    }

    return months; // Return the list of months
}

```