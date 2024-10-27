---
title: "Analyzing Neural Time Series Data: Theory and Practice"
itemType: "book"
publicationTitle: ""
bookTitle: ""
seriesTitle: ""
publisher: "The MIT Press"
place: ""
volume: ""
numberOfVolumes: ""
issue: ""
pages: ""
edition: ""
date: "2014-01-17"
DOI: ""
ISBN: "978-0-262-31955-3"
ISSN: ""
url: "https://direct.mit.edu/books/monograph/4013/Analyzing-Neural-Time-Series-DataTheory-and"
importance: 
status: incomplete
tags:
  - article
---

## Analyzing Neural Time Series Data: Theory and Practice

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 238







> Time-Frequency Power and Baseline Normalizations





- **Color**: #aaaaaa (Gray)
- **Date**: 2024-10-26 12:54 pm

---








> [[wavelet convolution]], [[filter-Hilbert]], [[short-window FFT]], [[multitap]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> This is not specific to EEG data but also characterizes the relationship between power and frequency of many signals, including radio, radiation from the Big Bang, natural images, and many more.





- **Color**: #f19837 (Orange)
- **Date**: 2024-10-26 12:57 pm

---








> [[power law]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 12:57 pm

---



#### Page 239







> The third limitation is that aggregating effects across subjects can be difficult with raw power values. This is because individual  differences in raw power are influenced by skull thickness, sulcal anatomy, cortical surface  area recruited, recording environment (e.g., scalp cleanliness and preparation and electrode  impedance), and other factors that are independent of the neurocognitive process under  investigation





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 1:00 pm

---







> ). The fourth limitation is that taskrelated changes in power can be difficult to disentangle from background activity (this is also  shown below). This is particularly the case for frequencies that generally tend to have higher  power or frequencies that tend to have higher power during baseline periods, such as alpha  activity over posterior parietal and occipital electrode





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 1:16 pm

---




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-239-x106-y389.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 12:58 pm

---



#### Page 240







> raw power values are not normally distributed because they cannot be negative and they are  strongly positively skewed. This limits the ability to apply parametric statistical analyses to  time-frequency power data.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 1:16 pm

---







> le, thef s1/hape  can be attenuated by taking the logarithm of the power values (Kiebel, Tallon-Baudry, and  Friston 2005)





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 1:17 pm

---







> by modeling the 1/f shape and removing that fitted function from the data  (Freeman 2006).





- **Color**: #e56eee (Magenta)
- **Date**: 2024-10-26 1:17 pm

---




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-240-x49-y72.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 1:18 pm

---



#### Page 241




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-241-x114-y135.png>)



> *(No annotated text)*




- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 3:16 pm

---







> The horizontal bar over baseline indicates the mean across the baseline time period, and t  and f are time and frequency points. Note that the baseline has no t subscript, indicating that  all time points within a frequency band use the baseline perio





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 2:42 pm

---



#### Page 242







> The baseline is a period of time, typically a few hundred milliseconds before the start of the trial, when little or no task-related processing is expected





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 2:49 pm

---



#### Page 243







> data. Typical decibel values  after trial averaging are in the range of ±1–4 dB.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 2:54 pm

---







> do not transform each trial to decibels separately  and then average.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 2:54 pm

---







> No matter what color scale you use, you should always plot a color bar with numerical labels for the lower and upper color limits alongside the plots in your figures





- **Color**: #a28ae5 (Purple)
- **Date**: 2024-10-26 3:14 pm

---




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-243-x100-y333.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 2:44 pm

---



#### Page 244




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-244-x62-y147.png>)



> *(No annotated text)*




- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 3:16 pm

---







> A related transform to percentage change is dividing power during the task by power during the baseline time period.




**Comment**: Isn't this just the decibel conversion procedure but with less steps? How can this take care of the 1/f nature of power.


- **Color**: #e56eee (Magenta)
- **Date**: 2024-10-26 3:20 pm

---



#### Page 245




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-245-x90-y343.png>)



> *(No annotated text)*




- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 3:40 pm

---







> The Z-transform differs from decibel and  percentage change because the latter two methods are based only on the average baseline  power, whereas the Z-transform is based both on the average baseline power and on the standard deviation of the baseline power over time. Because of this, estimates of stimulus-related  power may be adversely affected by highly variable data in the baseline period. This may be  an issue if you have noisy data or few trials.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 3:23 pm

---



#### Page 246




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-246-x53-y124.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 3:40 pm

---



#### Page 247




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-247-x70-y264.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 3:48 pm

---



#### Page 248








> [[empirical mode decomposition]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:58 pm

---








> [[Frobenius norm]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-26 2:59 pm

---







> For time-frequency power, linear baseline subtractions should be  avoided because they do not address 1/f power-law scaling.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 2:59 pm

---







> First, power values cannot be negative, which means that the distribution of power values  across trials is likely to be positively skewed. Second, for the same reason, outliers and other  nonrepresentative data are more likely to be larger than the mean, compared to smaller  than the mean, and therefore will bias the mean toward larger values. This is further exacerbated by the fact that power is amplitude squared. Thus, somewhat large amplitude values  become larger power values, and very large amplitude values, which may be outliers, become  extremely large power values. Therefore, there is a danger that with a relatively low trial  count and noisy data, outliers in one condition can skew the results to incorrectly suggest a  condition difference (Handelsman 2002).





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 3:51 pm

---



#### Page 249




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-249-x80-y398.png>)



> *(No annotated text)*



**Comment**: This can be used as a test to qualitatively assess the signal-to-noise ratio.


- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 3:54 pm

---



#### Page 250







> One situation in which the median might be preferred over the mean, or in addition to the  mean, is when there are few trials and noisy data.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 4:18 pm

---



#### Page 251







> Typically, power data are averaged across all trials, and then a baseline normalization is  applied. Performing baseline normalization on single trials prior to averaging helps minimize the influence of outlier trials but does not completely mitigate their impact, particularly for large outliers





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-26 4:22 pm

---




![](<0 - Supplementary/images/cohenAnalyzingNeuralTime2014.md/image-251-x107-y389.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-26 4:21 pm

---



#### Page 352







> For phase-based connectivity, you can use measures that are insensitive to volume  conduction such as imaginary coherence, phase-lag index, weighted phase-lag index, or  phase-slope-index.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---








> [[phase-based connectivity]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---








> [[imaginary coherence]], [[phase-lag index]], [[weighted phase-lag index]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---








> [[phase-slope-index]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 367







> Because effects of volume conduction are instantaneous within measurement capabilities of  M/EEG acquisition and within frequencies typically investigated in M/EEG research (Plonsey  and Heppner 1967; Stinstra and Peters 1998), spurious connectivity results that are caused by  two electrodes measuring activity from the same source will have phase lags of zero or π (π if  the electrodes are on opposite sides of the dipole).





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---





### Notes


No notes available.


%% begin notes %%

### Bookmark

- **Bookmark**: Page 217
- **Status**: #incomplete
- **Relevance**: 9.7
## Commentaries



%% end notes %%

## Appendix

### Authors


- [[Mike X. Cohen]] (author)



### Abstract

A comprehensive guide to the conceptual, mathematical, and implementational aspects of analyzing electrical brain signals, including data from MEG, EEG, an


### Formatted Bibliography

Cohen, M. X. (2014). _Analyzing Neural Time Series Data: Theory and Practice_. The MIT Press. [https://doi.org/10.7551/mitpress/9609.001.0001](https://doi.org/10.7551/mitpress/9609.001.0001)




### Attachments


- **PDF**: C:\Users\joaop\Zotero\storage\C3VYFTBS\Cohen - 2014 - Analyzing Neural Time Series Data Theory and Practice.pdf




### Collections


- books





### Backlinking


#### Metadata Links



- publisher: [[The MIT Press]]



- date: [[2014]]






%% Import Date: 2024-10-27T22:50:43.845+00:00 %%
