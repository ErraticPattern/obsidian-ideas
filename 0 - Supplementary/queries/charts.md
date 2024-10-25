### Biggest  Notes (File Size)

```dataviewjs
const tagPages = dv.pages();

var labels = [],
    wordCount = [];

// Loop through every note and add data to the above arrays
tagPages.forEach(note => {
    // add the name of the note
    labels.push(note.file.name);
    // add the word count for the note
    wordCount.push(note.file.size);
});

const chartData = {
    type: 'bar',
    data: {
        labels: labels,
        datasets: [{
            label: 'File Size',
            data: wordCount,
            backgroundColor: 'rgba(75, 192, 192, 0.2)',
            borderColor: 'rgba(75, 192, 192, 1)',
            borderWidth: 1
        }]
    },
    options: {
        responsive: true,
        scales: {
            y: {
                beginAtZero: true,
                title: {
                    display: true,
                    text: 'File Size (bytes)'
                }
            },
            x: {
                title: {
                    display: true,
                    text: 'File Name'
                }
            }
        },
        plugins: {
            tooltip: {
                callbacks: {
                    label: function(context) {
                        return context.dataset.label + ': ' + context.raw + ' bytes';
                    }
                }
            }
        }
    }
};

window.renderChart(chartData, this.container);
```
### Most Connected People 
```dataviewjs
const pages = dv.pages('#person');
var labels = [],
    backlinkCounts = [];

// Loop through every note and collect backlink data
pages.forEach(note => {
    labels.push(note.file.name);
    backlinkCounts.push(note.file.inlinks.length);
});

// Sort the data by backlink count in descending order
const sortedData = labels.map((label, index) => {
    return { label: label, count: backlinkCounts[index] };
}).sort((a, b) => b.count - a.count);

// Extract sorted labels and counts, but only take the top 10
const top10Data = sortedData.slice(0, 25);
labels = top10Data.map(data => data.label);
backlinkCounts = top10Data.map(data => data.count);

const chartData = {
    type: 'bar',
    data: {
        labels: labels,
        datasets: [{
            label: 'Number of Backlinks',
            data: backlinkCounts,
            backgroundColor: 'rgba(192, 192, 75, 0.2)',
            borderColor: 'rgba(192, 192, 75, 1)',
            borderWidth: 1
        }]
    },
    options: {
        responsive: true,
        scales: {
            y: {
                beginAtZero: true,
                title: {
                    display: true,
                    text: 'Number of Backlinks'
                }
            },
            x: {
                title: {
                    display: true,
                    text: 'Note Title'
                }
            }
        },
        plugins: {
            tooltip: {
                callbacks: {
                    label: function(context) {
                        return context.dataset.label + ': ' + context.raw;
                    }
                }
            }
        }
    }
};

window.renderChart(chartData, this.container);
```