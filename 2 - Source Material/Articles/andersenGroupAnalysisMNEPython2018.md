---
citekey: "andersenGroupAnalysisMNEPython2018"
title: "Group Analysis in MNE-Python of Evoked Responses from a Tactile Stimulation Paradigm: A Pipeline for Reproducibility at Every Step of Processing, Going from Individual Sensor Space Representations to an across-Group Source Space Representation"
itemType: "journalArticle"
publicationTitle: "Frontiers in Neuroscience"
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: "12"
numberOfVolumes: ""
issue: ""
pages: ""
edition: ""
date: "2018-01-22"
DOI: "10.3389/fnins.2018.00006"
ISBN: ""
ISSN: "1662-453X"
url: "https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2018.00006/full"
importance: 
status: incomplete
tags:
  - article
---

## Group Analysis in MNE-Python of Evoked Responses from a Tactile Stimulation Paradigm: A Pipeline for Reproducibility at Every Step of Processing, Going from Individual Sensor Space Representations to an across-Group Source Space Representation

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations


No annotations available.


### Notes


No notes available.


%% begin notes %%

<!-- Write your personal notes here -->

%% end notes %%

## Appendix

### Authors


- [[Lau M. Andersen]] (author)



### Abstract

<p>An important aim of an analysis pipeline for magnetoencephalographic data is that it allows for the researcher spending maximal effort on making the statistical comparisons that will answer the questions of the researcher, while in turn spending minimal effort on the intricacies and machinery of the pipeline. I here present a set of functions and scripts that allow for setting up a clear, reproducible structure for separating raw and processed data into folders and files such that minimal effort can be spend on: (1) double-checking that the right input goes into the right functions; (2) making sure that output and intermediate steps can be accessed meaningfully; (3) applying operations efficiently across groups of subjects; (4) re-processing data if changes to any intermediate step are desirable. Applying the scripts requires only general knowledge about the Python language. The data analyses are neural responses to tactile stimulations of the right index finger in a group of 20 healthy participants acquired from an Elekta Neuromag System. Two analyses are presented: going from individual sensor space representations to, respectively, an across-group sensor space representation and an across-group source space representation. The processing steps covered for the first analysis are filtering the raw data, finding events of interest in the data, epoching data, finding and removing independent components related to eye blinks and heart beats, calculating participants' individual evoked responses by averaging over epoched data and calculating a grand average sensor space representation over participants. The second analysis starts from the participants' individual evoked responses and covers: estimating noise covariance, creating a forward model, creating an inverse operator, estimating distributed source activity on the cortical surface using a minimum norm procedure, morphing those estimates onto a common cortical template and calculating the patterns of activity that are statistically different from baseline. To estimate source activity, processing of the anatomy of subjects based on magnetic resonance imaging is necessary. The necessary steps are covered here: importing magnetic resonance images, segmenting the brain, estimating boundaries between different tissue layers, making fine-resolution scalp surfaces for facilitating co-registration, creating source spaces and creating volume conductors for each subject.</p>


### Formatted Bibliography

Andersen, L. M. (2018). Group Analysis in MNE-Python of Evoked Responses from a Tactile Stimulation Paradigm: A Pipeline for Reproducibility at Every Step of Processing, Going from Individual Sensor Space Representations to an across-Group Source Space Representation. _Frontiers in Neuroscience_, _12_. [https://doi.org/10.3389/fnins.2018.00006](https://doi.org/10.3389/fnins.2018.00006)


### Tags


- #meg

- #analysis_pipeline

- #good_practice

- #group_analysis

- #minimum_norm_estimate_(mne)

- #mne-python

- #tactile_expectations




### Attachments


- **Full Text**: C:\Users\joaop\Zotero\storage\SA8DR52B\Andersen - 2018 - Group Analysis in MNE-Python of Evoked Responses f.pdf




### Collections


- meg





### Backlinking


#### Metadata Links


- publicationTitle: [[Frontiers in Neuroscience]]




- date: [[2018]]





<!-- Any additional notes or comments -->


%% Import Date: 2025-01-09T18:05:55.196+00:00 %%
