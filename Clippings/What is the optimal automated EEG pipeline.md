---
title: "What is the optimal automated EEG pipeline?"
source: "https://www.youtube.com/watch?v=mW7u2YEK3ZY&t=814s"
author:
  - "[[EEGLAB]]"
published: 2023-05-24
created: 2024-12-17
description: "What is the best EEG pipeline? This subject has been debated for several decades now, and it still is. Using a new metric to assess data quality, we try to find the optimal preprocessing pipeline for"
tags:
  - "clippings"
---
#
# Notes
# Content 
# Transcript
![](https://www.youtube.com/watch?v=mW7u2YEK3ZY)  

What is the best EEG pipeline? This subject has been debated for several decades now, and it still is. Using a new metric to assess data quality, we try to find the optimal preprocessing pipeline for 3 different experiments.  
  
0:00 Introduction  
0:34 Data quality metric and methodology  
2:41 Data used for finding optimal pipelines  
5:21 The effect of filtering  
8:19 Line noise removal  
9:12 Re-referencing  
9:42 Artifact rejection introduction  
10:53 Automated artifact rejection with MNE  
11:09 Automated artifact rejection with Brainstorm  
11:52 Automated artifact rejection with FieldTrip  
12:25 Automated artifact rejection with EEGLAB  
14:16 Why is EEG better left alone  
15:12 Baseline removal for ERPs  
15:32 Finding the optimal pipeline  
16:42 Comparison with multiverse analysis  
19:29 Are results consistent across approaches  
  
Pipeline code: https://github.com/sccn/eeg_pipelines  
  
References:  
\------------------  
Delorme A. EEG is better left alone. Sci Rep. 2023 Feb 9;13(1):2372. doi: 10.1038/s41598-023-27528-0. PMID: 36759667; PMCID: PMC9911389.  
https://www.nature.com/articles/s41598-023-27528-0  
  
Clayson PE, Baldwin SA, Rocha HA, Larson MJ. The data-processing multiverse of event-related potentials (ERPs): A roadmap for the optimization and standardization of ERP processing and reduction pipelines. Neuroimage. 2021 Dec 15;245:118712. doi: 10.1016/j.neuroimage.2021.118712. Epub 2021 Nov 17. PMID: 34800661.  
https://www.sciencedirect.com/science/article/pii/S1053811921009848?via%3Dihub
# Others
Thanks Mike X. Cohen!