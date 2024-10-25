---
start date: <%tp.date.now() %>
end date: 
id: 
  - <% tp.user.adler32_str() %>
  - <% await tp.system.prompt("Enter abbreviation:") %>
status: in progress
tags:
  - "#experiment"
aliases:
---
---
# Description


---
# Tasks
<%* 
// Fetch the first and second IDs
let first_id = tp.frontmatter.id && tp.frontmatter.id.length > 0 ? tp.frontmatter.id[0] : tp.user.adler32_str();
let second_id = tp.frontmatter.id && tp.frontmatter.id.length > 1 ? tp.frontmatter.id[1] : await tp.system.prompt("Please confirm the name:");
-%>
## To do
```dataview
TASK
WHERE contains(id, "<%* tR += first_id %>") OR contains(id, "<%* tR += second_id %>") AND ( length(id) <= 1 OR (length(id) > 1 AND contains(text, "🆔<%* tR += second_id %>")) )
WHERE !completed
```
## Completed (Last 10)
```dataview 
TASK
WHERE contains(id, "<%* tR += first_id %>") OR contains(id, "<%* tR += second_id %>") AND ( length(id) <= 1 OR (length(id) > 1 AND contains(text, "🆔<%* tR += second_id %>")) )
WHERE completed
LIMIT 10
```
# Files


---
# Entries
<% tp.date.now() %>