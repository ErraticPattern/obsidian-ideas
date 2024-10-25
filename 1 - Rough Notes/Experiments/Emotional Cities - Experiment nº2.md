---
start date: 2024-06-07
end date: 
id:
  - 3CEB0506
  - exp2
status: in progress
tags:
  - "#experiment"
aliases:
  - Exp.2
---
---
# Description


---
# Tasks
## To do
```dataview
TASK
WHERE contains(id,"3CEB0506") OR contains(id,"exp2") 
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp2"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE contains(id,"3CEB0506") OR contains(id,"exp2") 
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp2"))
)
WHERE completed
LIMIT 10
```
# Files
[[EGI software]]

---
# Entries
2024-06-07