---
start date: 2024-12-13
end date: 
id: 
  - 3CBD050F
  - neurocir
status: in progress
tags:
  - "#experiment"
aliases:
---
---
# Description
The goal is to create paradigms to assess functional activity on specific brain regions. These tasks will be performed by patients with [[Brain Tumors|brain tumors]], [[Epilepsy]], [[Aneurysm]], and [[Cerebral Arteriovenous Malformation]].

---
# Tasks
## To do
```dataview
TASK
WHERE contains(id, "3CB30509") OR contains(id, "neurocir") AND ( length(id) <= 1 OR (length(id) > 1 AND contains(text, "🆔neurocir")) )
WHERE !completed
```
## Completed (Last 10)
```dataview 
TASK
WHERE contains(id, "3CB30509") OR contains(id, "neurocir") AND ( length(id) <= 1 OR (length(id) > 1 AND contains(text, "🆔neurocir")) )
WHERE completed
LIMIT 10
```
# Files


---
# Entries
2024-12-13