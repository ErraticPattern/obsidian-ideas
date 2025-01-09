---
citekey: "michelEEGSourceImaging2019"
title: "EEG Source Imaging: A Practical Review of the Analysis Steps"
itemType: "journalArticle"
publicationTitle: "Frontiers in Neurology"
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: "10"
numberOfVolumes: ""
issue: ""
pages: ""
edition: ""
date: "2019-04-04"
DOI: "10.3389/fneur.2019.00325"
ISBN: ""
ISSN: "1664-2295"
url: "https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2019.00325/full"
importance: 
status: incomplete
tags:
  - article
---

## EEG Source Imaging: A Practical Review of the Analysis Steps

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 2







> Localization of a limited number of equivalent dipoles is the most classical approach to solve the inverse problem (7).





- **Color**: #ffd400 (Yellow)
- **Date**: 2025-01-05 12:52 am

---







> hese so-called distributed source localization methods do not  make a priori assumption with respect to the number of dipoles.





- **Color**: #ffd400 (Yellow)
- **Date**: 2025-01-05 12:52 am

---








> [[LAURA]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-29 10:56 pm

---



#### Page 3




![](<0 - Supplementary/images/michelEEGSourceImaging2019.md/image-3-x34-y458.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-12-31 6:19 pm

---







> Filtering the data can have important effects on the time-courses and the phases of the data (39, 40), as well as on the localization of the waveforms’ local extrema.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-30 2:44 pm

---








> [[Cartool]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-12-20 11:01 pm

---







> we implemented a non-causal, Infinite Impulse Response (IIR) Butterworth filter of 2nd order, known for its optimally flat passband response, which limits the artificial introduction of new local maxima





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-12-20 11:01 pm

---



#### Page 4








> [[EEGLAB]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-29 11:00 pm

---







> Even after interpolation of artifacted electrodes and removing irrelevant ICA components, transient events can corrupt a few electrodes for a short time period. They can be seen on the potential map displays as isolated “islands” within the local neighborhood. Such outlier electrodes will have dramatic effects on source localization as the steep gradients will lead to local maxima beneath the electrode





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-29 10:21 pm

---








> [[outliers]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-29 10:21 pm

---




![](<0 - Supplementary/images/michelEEGSourceImaging2019.md/image-4-x326-y631.png>)



> *(No annotated text)*




- **Color**: #aaaaaa (Gray)
- **Date**: 2024-12-20 11:27 pm

---








> [[MNI brain]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-12-20 11:30 pm

---



#### Page 5




![](<0 - Supplementary/images/michelEEGSourceImaging2019.md/image-5-x32-y515.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-29 11:00 pm

---



#### Page 11








> [[Tikhonov regularization]]





- **Color**: #5fb236 (Green)
- **Date**: 2025-01-02 5:43 pm

---







> it factors in the equations a level of EEG noise, and enforces a level of smoothness in the inverted results. The more regularization, the smoother the results and the less the sensitivity to noise. However, too much regularization, by over-smoothing the results, will degrade the accuracy of the localization.





- **Color**: #ffd400 (Yellow)
- **Date**: 2025-01-02 5:43 pm

---



#### Page 14







> In experimental studies, EEG source imaging has become standard to localize different brain areas involved in sensory, motor, and cognitive functions, most often applied to eventrelated potentials (89, 96).





- **Color**: #ffd400 (Yellow)
- **Date**: 2025-01-02 11:21 pm

---



#### Page 15







> It has thereby become clear that such connectivity measures have to be applied in source space and not on the level of the scalp electrodes, since volume conduction and reference-dependency make the interpretability of sensor-based connectivity measures difficult (105–110).





- **Color**: #ffd400 (Yellow)
- **Date**: 2025-01-05 12:51 am

---





### Notes


No notes available.


%% begin notes %%

<!-- Write your personal notes here -->

%% end notes %%

## Appendix

### Authors


- [[Christoph M. Michel]] (author)

- [[Denis Brunet]] (author)



### Abstract

<p>The electroencephalogram (EEG) is one of the oldest technologies to measure neuronal activity of the human brain. It has its undisputed value in clinical diagnosis, particularly (but not exclusively) in the identification of epilepsy and sleep disorders and in the evaluation of dysfunctions in sensory transmission pathways. With the advancement of digital technologies, the analysis of EEG has moved from pure visual inspection of amplitude and frequency modulations over time to a comprehensive exploration of the temporal and spatial characteristics of the recorded signals. Today, EEG is accepted as a powerful tool to capture brain function with the unique advantage of measuring neuronal processes in the time frame in which these processes occur, namely in the sub-second range. However, it is generally stated that EEG suffers from a poor spatial resolution that makes it difficult to infer to the location of the brain areas generating the neuronal activity measured on the scalp. This statement has challenged a whole community of biomedical engineers to offer solutions to localize more precisely and more reliably the generators of the EEG activity. High-density EEG systems combined with precise information of the head anatomy and sophisticated source localization algorithms now exist that convert the EEG to a true neuroimaging modality. With these tools in hand and with the fact that EEG still remains versatile, inexpensive and portable, electrical neuroimaging has become a widely used technology to study the functions of the pathological and healthy human brain. However, several steps are needed to pass from the recording of the EEG to 3-dimensional images of neuronal activity. This review explains these different steps and illustrates them in a comprehensive analysis pipeline integrated in a stand-alone freely available academic software: Cartool. The information about how the different steps are performed in Cartool is only meant as a suggestion. Other EEG source imaging software may apply similar or different approaches to the different steps.</p>


### Formatted Bibliography

Michel, C. M., & Brunet, D. (2019). EEG Source Imaging: A Practical Review of the Analysis Steps. _Frontiers in Neurology_, _10_. [https://doi.org/10.3389/fneur.2019.00325](https://doi.org/10.3389/fneur.2019.00325)


### Tags


- #eeg

- #head_model

- #inverse_model

- #pre-processing

- #source_localizatioon




### Attachments


- **Michel and Brunet - 2019 - EEG Source Imaging A Practical Review of the Analysis Steps.pdf**: I:\My Drive\literature\neuro\esi\Michel and Brunet - 2019 - EEG Source Imaging A Practical Review of the Analysis Steps.pdf




### Collections


- esi





### Backlinking


#### Metadata Links


- publicationTitle: [[Frontiers in Neurology]]




- date: [[2019]]





<!-- Any additional notes or comments -->


%% Import Date: 2025-01-09T18:06:02.701+00:00 %%
