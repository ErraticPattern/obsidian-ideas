---
title: An Automated Tool to Classify and Transform Unstructured MRI Data into BIDS Datasets
itemType: journalArticle
publicationTitle: Neuroinformatics
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: ""
numberOfVolumes: ""
issue: ""
pages: ""
edition: ""
date: 2024-03-26
DOI: 10.1007/s12021-024-09659-5
ISBN: ""
ISSN: 1559-0089
url: https://doi.org/10.1007/s12021-024-09659-5
importance: "4.5"
status: incomplete
tags:
  - article
---

## An Automated Tool to Classify and Transform Unstructured MRI Data into BIDS Datasets

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 2








> [[MRI]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:16 am

---








> [[SIENAX software]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:16 am

---








> [[Digital Imaging and Communications in Medicine]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:17 am

---








> [[DICOM standard]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:17 am

---








> [[DICOM headers]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:17 am

---



#### Page 6




![](<0 - Supplementary/images/bartnikAutomatedToolClassify2024.md/image-6-x40-y71.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 2:18 am

---



#### Page 8







> Since it relies generally on a heuristics approach, BIDScoin is limited by its ability to generalize across Series Descriptions or Protocol Names, which are some of the main attributes it uses for sorting DICOMs.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:46 pm

---








> [[dcm2niix]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:18 am

---








> [[NifTI]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:18 am

---








> [[HeuDiConv]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:17 am

---








> [[dcm2bids]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:17 am

---








> [[BIDScoin]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:18 am

---








> [[DeepDicomSort]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:18 am

---








> [[random forest model]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:18 am

---





### Notes


No notes available.


%% begin notes %%

### Bookmark

- **Bookmark**: Page <!-- Specify the page number or section -->
- **Status**: #incomplete
- **Relevance**: 4.5
## Commentaries



%% end notes %%

## Appendix

### Authors


- [[Alexander Bartnik]] (author)

- [[Sujal Singh]] (author)

- [[Conan Sum]] (author)

- [[Mackenzie Smith]] (author)

- [[Niels Bergsland]] (author)

- [[Robert Zivadinov]] (author)

- [[Michael G. Dwyer]] (author)



### Abstract

The increasing use of neuroimaging in clinical research has driven the creation of many large imaging datasets. However, these datasets often rely on inconsistent naming conventions in image file headers to describe acquisition, and time-consuming manual curation is necessary. Therefore, we sought to automate the process of classifying and organizing magnetic resonance imaging (MRI) data according to acquisition types common to the clinical routine, as well as automate the transformation of raw, unstructured images into Brain Imaging Data Structure (BIDS) datasets. To do this, we trained an XGBoost model to classify MRI acquisition types using relatively few acquisition parameters that are automatically stored by the MRI scanner in image file metadata, which are then mapped to the naming conventions prescribed by BIDS to transform the input images to the BIDS structure. The model recognizes MRI types with 99.475% accuracy, as well as a micro/macro-averaged precision of 0.9995/0.994, a micro/macro-averaged recall of 0.9995/0.989, and a micro/macro-averaged F1 of 0.9995/0.991. Our approach accurately and quickly classifies MRI types and transforms unstructured data into standardized structures with little-to-no user intervention, reducing the barrier of entry for clinical scientists and increasing the accessibility of existing neuroimaging data.


### Formatted Bibliography

Bartnik, A., Singh, S., Sum, C., Smith, M., Bergsland, N., Zivadinov, R., & Dwyer, M. G. (2024). An Automated Tool to Classify and Transform Unstructured MRI Data into BIDS Datasets. _Neuroinformatics_. [https://doi.org/10.1007/s12021-024-09659-5](https://doi.org/10.1007/s12021-024-09659-5)


### Tags


- #bids

- #automation

- #data_curation

- #machine_learning

- #magnetic_resonance_imaging

- #reproducibility




### Attachments


- **Full Text PDF**: C:\Users\joaop\Zotero\storage\DU4P82PR\Bartnik et al. - 2024 - An Automated Tool to Classify and Transform Unstru.pdf




### Collections


- mri





### Backlinking


#### Metadata Links


- publicationTitle: [[Neuroinformatics]]




- date: [[2024]]





<!-- Any additional notes or comments -->


%% Import Date: 2024-10-26T02:19:13.211+01:00 %%
