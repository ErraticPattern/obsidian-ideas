---
start date: 2024-06-07
end date: 
id:
  - 3D3E0516
  - exp1
status: in progress
tags:
  - "#experiment"
aliases:
  - Exp.1
---
---
# Description


---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3D3E0516") OR contains(id, "exp1"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp1"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3D3E0516") OR contains(id, "exp1"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp1"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-06-07