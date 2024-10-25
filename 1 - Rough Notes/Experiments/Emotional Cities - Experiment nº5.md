---
start date: 2024-06-07
end date: 
id:
  - 3D05050C
  - exp5
status: in progress
tags:
  - "#experiment"
aliases:
  - Exp.5
---
---
# Description


---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3D05050C") OR contains(id, "exp5"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp5"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3D05050C") OR contains(id, "exp5"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp5"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-06-07