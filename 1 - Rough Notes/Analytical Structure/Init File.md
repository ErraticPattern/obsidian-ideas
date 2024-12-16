---
creation date: 2024-09-06 22:41
aliases: 
tags:
  - baby
modification date: Friday, 6th September 2024, 22:41:25
id:
---
---

## Parent note
[[Config File]]---
## Backlinking


---
# Init File
The `init` file should hold metadata from the current study. This metadata will be used to construct the template folder.
```matlab
init = struct()
# Metadata
init.experiment = 'eMotional Cities Experiment 4'
init.short = 'exp4' 
init.taskname = 'videorating'
init.authors  = 'João Amaro'
# Hardware
init.ram = '16 GB'
# Software
init.os = {'windows 11', 'linux'}
init.motherlanguage = 'matlab'
init.ide = 'cursor'
init.programming = {'matlab', 'python', 'docker'}
# Data types
init.eeg = 'yes'
init.mri = 'yes'
init.eeg.original_format = 'mff'
init.eeg.bids_format = 'vhdr'
# Behavioral
init.beh =  'yes'
init.assessments = {'panas', 'bisbas', 'hexaco'} 
```

---
# Notes


---
## Links
- [Google Search](https://www.google.com/search?q=Init+File)

---
# Bibliography
+ 