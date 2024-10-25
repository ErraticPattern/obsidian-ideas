---
start date: 2024-06-07
end date: 
id:
  - 3CF9050F
  - exp3
status: in progress
tags:
  - "#experiment"
aliases:
  - Exp.3
---
---
# Description


---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3CF9050F") OR contains(id, "exp3"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp3"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3CF9050F") OR contains(id, "exp3"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp3"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-06-07