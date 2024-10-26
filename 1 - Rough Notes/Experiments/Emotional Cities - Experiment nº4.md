---
start date: 2024-06-07
end date: 
id:
  - 3D460516
  - exp4
status: in progress
tags:
  - "#experiment"
aliases:
  - Exp.4
---
---
# Description
Data organization:
- Motion-BIDS:

| [[Optical Motion Tracking]] | [[Virtual Reality]] | [[inertial measurement units]] | [[global positioning system]] |
| --------------------------- | ------------------- | ------------------------------ | ----------------------------- |
| No                          | No                  | Yes                            | Yes                              |

---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3D460516") OR contains(id, "exp4"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp4"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3D460516") OR contains(id, "exp4"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔exp4"))
)
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-06-07