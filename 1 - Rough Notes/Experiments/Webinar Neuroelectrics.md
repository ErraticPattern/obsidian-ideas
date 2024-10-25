---
start date: 2024-06-14
end date: 
id:
  - 3CF20512
  - ne_webinar
status: in progress
tags:
  - "#experiment"
aliases:
---
---
# Description

Presenting at a webinar about the use of Neuroelectrics' EEG products.

---
# Tasks
## To do
```dataview
TASK
WHERE (contains(id, "3CF20512") OR contains(id, "ne_webinar"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔ne_webinar"))
)
WHERE !completed
```
## Completed (Last 10)
```dataview
TASK
WHERE (contains(id, "3CF20512") OR contains(id, "ne_webinar"))
AND (
  length(id) <= 1 
  OR (length(id) > 1 AND contains(text, "🆔ne_webinar"))
)
WHERE completed
LIMIT 10
```

# Files


---
# Entries
2024-06-14