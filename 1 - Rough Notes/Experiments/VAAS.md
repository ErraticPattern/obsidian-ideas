---
start date: 2024-06-07
end date: 2024-12-03
id:
  - 3CCE0508
  - vaas
status: done
tags:
  - "#experiment"
aliases:
  - vaas
---
---
# Description
Crazy project and experience. I should keep track of which days I am busy doing acquisitions, for later pay.

---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3CCE0508") OR contains(id, "vaas"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔vaas"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3CCE0508") OR contains(id, "vaas"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔vaas"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-06-07