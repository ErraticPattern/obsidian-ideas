---
start date: 2024-10-01
end date: 
id:
  - 3C0204F6
  - psychiatry
status: in progress
tags:
  - "#experiment"
aliases:
---
---
# Description


---
# Tasks
## To do
```dataview
TASK
WHERE contains(id,"3C0204F6") OR contains(id,"psychiatry") 
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔psychiatry"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview 
TASK
WHERE contains(id,"3C0204F6") OR contains(id,"psychiatry") 
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔psychiatry"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-10-01