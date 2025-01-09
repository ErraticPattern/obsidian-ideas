---
citekey: "parraRecipesLinearAnalysis2005"
title: "Recipes for the linear analysis of EEG"
itemType: "journalArticle"
publicationTitle: "NeuroImage"
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: "28"
numberOfVolumes: ""
issue: "2"
pages: "326-341"
edition: ""
date: "2005-11-01"
DOI: "10.1016/j.neuroimage.2005.05.032"
ISBN: ""
ISSN: "1053-8119"
url: "https://www.sciencedirect.com/science/article/pii/S1053811905003381"
importance: 
status: incomplete
tags:
  - article
---

## Recipes for the linear analysis of EEG

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 2








> [[skin potentials]], [[myographic activity]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 11:02 pm

---








> [[inductive line noise]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 11:03 pm

---







> Since electrical potentials add linearly, we can summarize the electrodes’ activities as x1(t) = s(t) + n1(t) and x2(t) = s(t) + n2(t). Choosing equal weights, wT = [1,1], for the two neighboring electrodes in Eq. (1) results in a component, y(t) = 2s(t) + n1(t) + n2(t). This component captures the neuronal activity, s(t), with an increased signal-to-noise ratio relative to the individual electrodes




**Comment**: The idea is that signal summation increases snr. This is a good argument to use clusters of electrodes when possible.


- **Color**: #ff6666 (Red)
- **Date**: 2024-11-05 11:06 pm

---







> 3 dB improvement in the case of independent Gaussian noise





- **Color**: #e56eee (Magenta)
- **Date**: 2024-11-05 11:04 pm

---







> This paper shows how three basic criteria, namely maximum difference, maximum power, and statistical independence, can be used to select useful linear integration vectors w.




**Comment**: The choice of the weighting vector is the most important one.


- **Color**: #ffd400 (Yellow)
- **Date**: 2024-11-05 11:08 pm

---








> [[penalized logistic regression]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 11:33 pm

---








> [[support vector  machine]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 11:33 pm

---



#### Page 7







> Eye blinks cause a strong deflection of the EEG signal from baseline lasting 50 – 100 ms. Relative to a common reference the potentials are negative for electrodes placed below the eyes and positive for electrodes above.





- **Color**: #ff6666 (Red)
- **Date**: 2024-11-05 3:35 pm

---



#### Page undefined








> [[signal-to-noise ratio]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 3:42 pm

---







> Traditional EEG analysis methods such as trial-averaging typically only considers the time course of individual channels. Thus, the increased number of sensors has created a need for tools that can analyze the time series of multiple electrodes simultaneously.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-11-05 2:44 pm

---







> The methods presented in this paper avoid making any spatial modeling assumptions with regard to the sources or anatomy. They instead rely entirely on the statistics of the observed data and its covariation with observable stimuli and behavioral responses.




**Comment**: I think EEG methods can be broadly categorized by this criteria.


- **Color**: #ffd400 (Yellow)
- **Date**: 2024-11-05 3:41 pm

---








> [[EEG]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 3:42 pm

---




![](<0 - Supplementary/images/parraRecipesLinearAnalysis2005.md/image-undefined-x301-y236.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-11-05 3:45 pm

---








> [[temporal filtering]], [[trial averaging]], [[frequency power analysis]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-11-05 3:44 pm

---







> When compared to an individual sensor the projection y(t) sometimes also called a component – can be a better estimate of neurophysiological activity





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-11-05 11:01 pm

---





### Notes


No notes available.


%% begin notes %%

### Bookmark

- **Bookmark**: Page <!-- Specify the page number or section -->
- **Status**: #incomplete
- **Relevance**: 7.4
## Commentaries

$$
y(t)=\mathbf{w}^{T}\mathbf{x}(t)=\sum_{i=1}^{D}w_{i}x_{i}(t).
$$

%% end notes %%

## Appendix

### Authors


- [[Lucas C. Parra]] (author)

- [[Clay D. Spence]] (author)

- [[Adam D. Gerson]] (author)

- [[Paul Sajda]] (author)



### Abstract

In this paper, we describe a simple set of “recipes” for the analysis of high spatial density EEG. We focus on a linear integration of multiple channels for extracting individual components without making any spatial or anatomical modeling assumptions, instead requiring particular statistical properties such as maximum difference, maximum power, or statistical independence. We demonstrate how corresponding algorithms, for example, linear discriminant analysis, principal component analysis and independent component analysis, can be used to remove eye-motion artifacts, extract strong evoked responses, and decompose temporally overlapping components. The general approach is shown to be consistent with the underlying physics of EEG, which specifies a linear mixing model of the underlying neural and non-neural current sources.


### Formatted Bibliography

Parra, L. C., Spence, C. D., Gerson, A. D., & Sajda, P. (2005). Recipes for the linear analysis of EEG. _NeuroImage_, _28_(2), 326–341. [https://doi.org/10.1016/j.neuroimage.2005.05.032](https://doi.org/10.1016/j.neuroimage.2005.05.032)


### Tags


- #brain_computer_interfaces

- #electroencephalography_(eeg)

- #generalized_eigenvalue_decomposition

- #linear_integration

- #source_estimation




### Attachments


- **Parra et al. - 2005 - Recipes for the linear analysis of EEG.pdf**: C:\Users\joaop\Zotero\storage\9TZQ4PFZ\Parra et al. - 2005 - Recipes for the linear analysis of EEG.pdf

- **ScienceDirect Snapshot**: C:\Users\joaop\Zotero\storage\M7Z6TXD2\S1053811905003381.html




### Collections


- process





### Backlinking


#### Metadata Links


- publicationTitle: [[NeuroImage]]




- date: [[2005]]






%% Import Date: 2025-01-09T18:07:49.985+00:00 %%
