---
creation date: <% tp.file.creation_date() %>
aliases: 
tags:
  - tasks
modification date: 
end date: 
id:
---
<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>
# <% tp.file.title %>
---
## Topics
+ 
---
## To do
- [ ] 