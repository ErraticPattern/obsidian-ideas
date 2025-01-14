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

## Head Model Creation
* sub-NSNP807
	* Head Model ID: 355-2023
	* Need to manually change ID - done.
* sub-NSNP905
	* Head Model ID: NSNP905_S2011
	* Need to manually change ID - done.
* sub-NSNP907
	* Head Model ID: NSNP907_S2011
	* Need to manually change ID - done.
* sub-NSNP812
	* No editing and added a 350 mm distance of nasion to inion to adjust the geoscan file. This structural data contained two slices of artifacts which are most likely due to the transition from one hemisphere to the other.
* sub-NSNP808
	*  No editing and added a 360 mm distance of nasion to inion to adjust the geoscan file. This structural data contained two slices of artifacts which are most likely due to the transition from one hemisphere to the other.
* sub-NSNP804
	*  No editing and added a 360 mm distance of nasion to inion to adjust the geoscan file. This structural data contained two slices of artifacts which are most likely due to the transition from one hemisphere to the other.
* sub-NSNP815
	*  No editing and added a 380 mm distance of nasion to inion to adjust the geoscan file. I opted for the default geoscan file since the custom scan had poor quality (see images in folder). This structural data contained two slices of artifacts which are most likely due to the transition from one hemisphere to the other.
* sub-NSNP811
	*  This scan is incomplete and therefore its head model is ***unusable***. No editing. Geoscan file cannot be applied since mri scan does not cover the chin part of the face. This structural data contained two slices of artifacts which are most likely due to the transition from one hemisphere to the other.

---
## Custom Events
The following were the last sets of data to get the custom events using the Markup tool in Net Station Tools. Each one of these datasets have corresponding head models (NSNP807 is not included since it was the pilot data).
+ NSNP804
+ NSNP805
+ NSNP808
+ NSNP811
+ NSNP812
+ NSNP813
+ NSNP815
+ NSNP905
+ NSNP907

---
## Notes
- I discovered it is possible to change the subject ID in the head model itself which means that I no longer need to specify and mofidy the data's subject ID.
- MRI data seems to have artifacts from headphones (used to cancel noise).