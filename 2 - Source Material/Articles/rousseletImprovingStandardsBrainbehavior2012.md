---
citekey: "rousseletImprovingStandardsBrainbehavior2012"
title: "Improving standards in brain-behavior correlation analyses"
itemType: "journalArticle"
publicationTitle: "Frontiers in Human Neuroscience"
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: "6"
numberOfVolumes: ""
issue: ""
pages: ""
edition: ""
date: "2012-05-03"
DOI: "10.3389/fnhum.2012.00119"
ISBN: ""
ISSN: "1662-5161"
url: "https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2012.00119/full"
importance: 
status: incomplete
tags:
  - article
---

## Improving standards in brain-behavior correlation analyses

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 2








> [[minimum covariance determinant estimator]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> One particularly successful technique is the skipped correlation: it involves multivariate outlier detection using a projection technique (Wilcox, 2004, 2005). First, a robust estimator of multivariate location and scatter, for instance the minimum covariance determinant estimator MCD, (Rousseeuw, 1984; Rousseeuw and van Driessen, 1999; Hubert et al., 2008) is computed. Second, data points are orthogonally projected on lines joining each of the data point to the location estimator (that is to the middle of the data points with minimum scatter). Third, outliers are detected using a robust technique. Finally, Spearman correlations are computed on the remaining data points and calculations are adjusted by taking into account the dependency among the remaining data points.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---








> [[outliers]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> A first step in interpreting correlation analyses is to have a careful look at scatterplots, to detect situations involving marginal outliers and non-linear associations.





- **Color**: #a28ae5 (Purple)
- **Date**: 2024-10-25 8:47 pm

---







> One limitation of Pearson correlation is of course its strongest sensitivity to linear relationships: Pearson correlation can only be maximum when two variables are linearly related to each other, whereas Spearman correlation can be maximum when two variables are monotonically related, whether the relationship is linear or not





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---







> This is a critical problem, particularly true with Pearson correlation, but also all the techniques that rely on an ordinary least square solution: one badly positioned point can have a dramatic influence on the results (Hubert et al., 2008).





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---




![](<0 - Supplementary/images/rousseletImprovingStandardsBrainbehavior2012.md/image-2-x31-y61.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 3







> Because in many situations, researchers have weak or no priors, it seems safer to use robust outlier detection techniques rather than risking reporting and interpreting erroneous correlations.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 5







> Multiple correlations are often performed between one behavioral measure and several brain areas, with the goal of identifying the brain area with the strongest correlation.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Only few of the papers we surveyed provided quantitative tests of the difference between correlations. Instead, most authors described implicitly or explicitly a significant correlation as being different from a non-significant correlation, a statistical fallacy covered in more details by (Nieuwenhuis et al., 2011).





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---







> To compare correlations between brain areas, a formal test between correlation coefficients must be performed. This is best achieved using a percentile bootstrap test of the differences between correlations, with special adjustments in the case of Pearson correlation (Wilcox, 2009, 2012).





- **Color**: #a28ae5 (Purple)
- **Date**: 2024-10-25 8:47 pm

---



#### Page undefined







> Recently, problems with correlations have received a lot of attention in the brain imaging community. Notably, some high correlations between fMRI brain activations and behavior or personality traits appear to be due to circularity in the analyses (Vul et al., 2009a,b); in other cases, correlations can be introduced by uncontrolled underlying factors, such as age (Lazic, 2010).





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> One of the main issues with the detection and quantification of associations is the sensitivity of the estimator to outliers.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> An outlier is defined as “an observation (or subset of observations), which appears to be inconsistent with the remainder of that sets of data” (Barnett and Lewis, 1994).





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---








> [[Pearson correlation]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> The most widely used technique to assess brain-behavior associations is Pearson correlation, a non-robust technique particularly sensitive to outliers (Wilcox, 2004, 2005).





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> In addition to its’ sensitivity to outliers, Pearson correlation is also affected by the magnitude of the slope around which points are clustered, curvature, the magnitude of the residuals, restriction of range, and heteroscedasticity (Wilcox, 2012).





- **Color**: #e56eee (Magenta)
- **Date**: 2024-10-25 8:47 pm

---








> [[Spearman correlation]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---








> [[false positive]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---








> [[marginal distributions]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> Unfortunately, classic outlier detection techniques can have low power because they mainly rely on marginal distributions, whereas multivariate approaches perform better (Rousseeuw and Leroy, 1987; Iglewicz and Hoaglin, 1993; Barnett and Lewis, 1994; Hubert et al., 2008;  Wilcox, 2012). Thus, outlier detection using univariate techniques does not prevent erroneous estimates.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> exacerbated by a strong tendency in the literature to draw conclusions about all effects associated with a p-value inferior to 0.05, with a lack of consideration for effect sizes and confidence intervals.




**Comment**: Always consider the effect sizes and confidence intervals.


- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Because of its sensitivity to outliers, Pearson correlation is a poor tool to assess the existence of a relationship between two variables.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---








> [[skipped correlation]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> Spearman correlation is less sensitive to univariate (marginal) outliers. For this reason, Spearman correlation is called an M-measure of association.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---








> [[M-measure of association]]





- **Color**: #5fb236 (Green)
- **Date**: 2024-10-25 8:47 pm

---







> Spearman correlation consists in applying Pearson’s equation to the rank of the data.





- **Color**: #ff6666 (Red)
- **Date**: 2024-10-25 8:47 pm

---







> However, Spearman correlation, like Pearson correlation, is sensitive to bivariate outliers and several techniques have been proposed to detect such outliers (Wilcox, 2005).





- **Color**: #e56eee (Magenta)
- **Date**: 2024-10-25 8:47 pm

---





### Notes


No notes available.


%% begin notes %%

### Bookmark

- **Bookmark**: Page <!-- Specify the page number or section -->
- **Status**: #incomplete
- **Relevance**: 8.8
## Commentaries



%% end notes %%

## Appendix

### Authors


- [[Guillaume A. Rousselet]] (author)

- [[Cyril R. Pernet]] (author)



### Abstract

<p>Associations between two variables, for instance between brain and behavioral measurements, are often studied using correlations, and in particular Pearson correlation. However, Pearson correlation is not robust: outliers can introduce false correlations or mask existing ones. These problems are exacerbated in brain imaging by a widespread lack of control for multiple comparisons, and several issues with data interpretations. We illustrate these important problems associated with brain-behavior correlations, drawing examples from published articles. We make several propositions to alleviate these problems.</p>


### Formatted Bibliography

Rousselet, G. A., & Pernet, C. R. (2012). Improving standards in brain-behavior correlation analyses. _Frontiers in Human Neuroscience_, _6_. [https://doi.org/10.3389/fnhum.2012.00119](https://doi.org/10.3389/fnhum.2012.00119)


### Tags


- #confidence_intervals

- #multiple_comparisons

- #multivariate_statistics

- #outliers

- #pearson_correlation

- #robust_statistics

- #skipped_correlation

- #spearman_correlation




### Attachments


- **Full Text**: C:\Users\joaop\Zotero\storage\UV5ZISLV\Rousselet and Pernet - 2012 - Improving standards in brain-behavior correlation analyses.pdf




### Collections


- stats





### Backlinking


#### Metadata Links


- publicationTitle: [[Frontiers in Human Neuroscience]]




- date: [[2012]]






%% Import Date: 2025-01-09T18:06:05.267+00:00 %%
