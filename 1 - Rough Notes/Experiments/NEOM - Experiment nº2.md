---
start date: 2022-11-01
end date: 2023-11-30
id:
  - 3C880501
  - neom2
status: done
tags:
  - "#experiment"
aliases:
  - NEOM
---
---
# Description
My work consisted only of helping clean the EEG caps. I got 1,000€ for it so it was not bad at all.

---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3C880501") OR contains(id, "neom2"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔neom2"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3C880501") OR contains(id, "neom2"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔neom2"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-06-12