---
citekey: "liFirstStepNeuroimaging2016"
title: "The first step for neuroimaging data analysis: DICOM to NIfTI conversion"
itemType: "journalArticle"
publicationTitle: "Journal of Neuroscience Methods"
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: "264"
numberOfVolumes: ""
issue: ""
pages: "47-56"
edition: ""
date: "2016-05-01"
DOI: "10.1016/j.jneumeth.2016.03.001"
ISBN: ""
ISSN: "0165-0270"
url: "https://www.sciencedirect.com/science/article/pii/S0165027016300073"
importance: 
status: incomplete
tags:
  - article
---

## The first step for neuroimaging data analysis: DICOM to NIfTI conversion

### Table of Contents

- [Annotations](#annotations)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 3







> DICOM describes a tag based format, where each object in the file is encapsulated in a tag that describes the purpose and size of that chunk of data. Typically, the earlier objects store information about the participant, the device, the imaging sequence, and the image specifics (e.g. dimensions of the image), while the final object encodes the image data itself. Each object contains, in order, a Tag, an optional Value Representation (VR), a Length and the Value of the object itself (Table 1).





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> A Tag is a two-number code (e.g. “0028, 0010”) defining the meaning of the element. What the element exactly means relies on a so-called DICOM dictionary. The DICOM standard defines a dictionary for a large number of variables, referred to as the public tags. In addition, the standard also allows manufacturers to define their own tags, so-called private tags. The first element of the two-number code of public tags is always even, whereas it is odd for the vendor-specific private tags.





- **Color**: #2ea8e5 (Blue)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 4







> The optional second component in an object, VR, is a two-character code defining the data type of the value in the object. For example, “US” refers to unsigned short integer(s), “DS” refers to decimal string, etc.





- **Color**: #2ea8e5 (Blue)
- **Date**: 2024-10-25 8:47 pm

---







> The next component (Length) defines number of bytes of the stored value, while the final component encodes the Value itself. The Length provides the information needed to determine where the next object in the file begins.





- **Color**: #f19837 (Orange)
- **Date**: 2024-10-25 8:47 pm

---







> There can be many objects in a DICOM file (typically about a hundred, but there can be three orders of magnitude more for multi-frame DICOM).





- **Color**: #f19837 (Orange)
- **Date**: 2024-10-25 8:47 pm

---




![](<0 - Supplementary/images/liFirstStepNeuroimaging2016.md/image-4-x42-y180.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 6




![](<0 - Supplementary/images/liFirstStepNeuroimaging2016.md/image-6-x42-y293.png>)



> *(No annotated text)*




- **Color**: #f19837 (Orange)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 8




![](<0 - Supplementary/images/liFirstStepNeuroimaging2016.md/image-8-x41-y385.png>)



> *(No annotated text)*




- **Color**: #f19837 (Orange)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 10




![](<0 - Supplementary/images/liFirstStepNeuroimaging2016.md/image-10-x40-y494.png>)



> *(No annotated text)*




- **Color**: #f19837 (Orange)
- **Date**: 2024-10-25 8:47 pm

---





### Notes


No notes available.


%% begin notes %%

<!-- Write your personal notes here -->

%% end notes %%

## Appendix

### Authors


- [[Xiangrui Li]] (author)

- [[Paul S. Morgan]] (author)

- [[John Ashburner]] (author)

- [[Jolinda Smith]] (author)

- [[Christopher Rorden]] (author)



### Abstract

Background
Clinical imaging data are typically stored and transferred in the DICOM format, whereas the NIfTI format has been widely adopted by scientists in the neuroimaging community. Therefore, a vital initial step in processing the data is to convert images from the complicated DICOM format to the much simpler NIfTI format. While there are a number of tools that usually handle DICOM to NIfTI conversion seamlessly, some variations can disrupt this process.
New method
We provide some insight into the challenges faced with image conversion. First, different manufacturers implement the DICOM format differently which complicates the conversion. Second, different modalities and sub-modalities may need special treatment during conversion. Lastly, the image transferring and archiving can also impact the DICOM conversion.
Results
We present results in several error-prone domains, including the slice order for functional imaging, phase encoding direction for distortion correction, effect of diffusion gradient direction, and effect of gantry correction for some imaging modality.
Comparison with existing methods
Conversion tools are often designed for a specific manufacturer or modality. The tools and insight we present here are aimed at different manufacturers or modalities.
Conclusions
The imaging conversion is complicated by the variation of images. An understanding of the conversion basics can be helpful for identifying the source of the error. Here we provide users with simple methods for detecting and correcting problems. This also serves as an overview for developers who wish to either develop their own tools or adapt the open source tools created by the authors.


### Formatted Bibliography

Li, X., Morgan, P. S., Ashburner, J., Smith, J., & Rorden, C. (2016). The first step for neuroimaging data analysis: DICOM to NIfTI conversion. _Journal of Neuroscience Methods_, _264_, 47–56. [https://doi.org/10.1016/j.jneumeth.2016.03.001](https://doi.org/10.1016/j.jneumeth.2016.03.001)


### Tags


- #dicom

- #neuroimaging

- #nifti




### Attachments


- **ScienceDirect Snapshot**: C:\Users\joaop\Zotero\storage\SJF3U53D\S0165027016300073.html

- **Submitted Version**: C:\Users\joaop\Zotero\storage\FRW9G3KU\Li et al. - 2016 - The first step for neuroimaging data analysis DIC.pdf




### Collections


- mri





### Backlinking


#### Metadata Links


- publicationTitle: [[Journal of Neuroscience Methods]]




- date: [[2016]]





<!-- Any additional notes or comments -->


%% Import Date: 2025-01-09T18:09:20.888+00:00 %%
