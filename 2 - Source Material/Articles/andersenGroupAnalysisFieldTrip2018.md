---
citekey: "andersenGroupAnalysisFieldTrip2018"
title: "Group Analysis in FieldTrip of Time-Frequency Responses: A Pipeline for Reproducibility at Every Step of Processing, Going From Individual Sensor Space Representations to an Across-Group Source Space Representation"
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
date: "2018-05-01"
DOI: "10.3389/fnins.2018.00261"
ISBN: ""
ISSN: "1662-453X"
url: "https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2018.00261/full"
importance: 
status: incomplete
tags:
  - article
---

## Group Analysis in FieldTrip of Time-Frequency Responses: A Pipeline for Reproducibility at Every Step of Processing, Going From Individual Sensor Space Representations to an Across-Group Source Space Representation

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 11







> Following the suggestions for good practice by Gross et al. (2013) one should describe the ICA algorithm (runica: Code Snippet 5), the input data to the algorithm (the epoched  data: Code Snippet 5), the number of components estimated (60: Code Snippet 5), the number of components removed (two components: Figure 5) and the criteria for removing them [the likeness to eye blink, eye movements, and heart beat templates (Hyvärinen and Oja, 2000; Ikeda and Toyama, 2000; Jung et al., 2000) and seeing activity in the time courses of the components corresponding to what is recorded with electrooculographic and electrocardiographic channels (can be plotted with plot_ica from plot_sensor_space.m)].





- **Color**: #a28ae5 (Purple)
- **Date**: 2024-10-25 8:46 pm

---





### Notes


No notes available.


%% begin notes %%

<!-- Write your personal notes here -->

%% end notes %%

## Appendix

### Authors


- [[Lau M. Andersen]] (author)



### Abstract

<p>An important aim of an analysis pipeline for magnetoencephalographic (MEG) data is that it allows for the researcher spending maximal effort on making the statistical comparisons that will answer his or her questions. The example question being answered here is whether the so-called beta rebound differs between novel and repeated stimulations. Two analyses are presented: going from individual sensor space representations to, respectively, an across-group sensor space representation and an across-group source space representation. The data analyzed are neural responses to tactile stimulations of the right index finger in a group of 20 healthy participants acquired from an Elekta Neuromag System. The processing steps covered for the first analysis are MaxFiltering the raw data, defining, preprocessing and epoching the data, cleaning the data, finding and removing independent components related to eye blinks, eye movements and heart beats, calculating participants' individual evoked responses by averaging over epoched data and subsequently removing the average response from single epochs, calculating a time-frequency representation and baselining it with non-stimulation trials and finally calculating a grand average, an across-group sensor space representation. The second analysis starts from the grand average sensor space representation and after identification of the beta rebound the neural origin is imaged using beamformer source reconstruction. This analysis covers reading in co-registered magnetic resonance images, segmenting the data, creating a volume conductor, creating a forward model, cutting out MEG data of interest in the time and frequency domains, getting Fourier transforms and estimating source activity with a beamformer model where power is expressed relative to MEG data measured during periods of non-stimulation. Finally, morphing the source estimates onto a common template and performing group-level statistics on the data are covered. Functions for saving relevant figures in an automated and structured manner are also included. The protocol presented here can be applied to any research protocol where the emphasis is on source reconstruction of induced responses where the underlying sources are not coherent.</p>


### Formatted Bibliography

Andersen, L. M. (2018). Group Analysis in FieldTrip of Time-Frequency Responses: A Pipeline for Reproducibility at Every Step of Processing, Going From Individual Sensor Space Representations to an Across-Group Source Space Representation. _Frontiers in Neuroscience_, _12_. [https://doi.org/10.3389/fnins.2018.00261](https://doi.org/10.3389/fnins.2018.00261)


### Tags


- #meg

- #analysis_pipeline

- #good_practice

- #group_analysis

- #tactile_expectations

- #beamformer

- #fieldtrip




### Attachments


- **Full Text**: C:\Users\joaop\Zotero\storage\R2MFCPG9\Andersen - 2018 - Group Analysis in FieldTrip of Time-Frequency Resp.pdf




### Collections


- eeg





### Backlinking


#### Metadata Links


- publicationTitle: [[Frontiers in Neuroscience]]




- date: [[2018]]





<!-- Any additional notes or comments -->


%% Import Date: 2025-01-09T18:05:55.186+00:00 %%
