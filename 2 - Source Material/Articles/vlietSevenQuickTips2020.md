---
title: Seven quick tips for analysis scripts in neuroimaging
itemType: journalArticle
publicationTitle: PLOS Computational Biology
bookTitle: ""
seriesTitle: ""
publisher: ""
place: ""
volume: "16"
numberOfVolumes: ""
issue: "3"
pages: e1007358
edition: ""
date: 2020-03-26
DOI: 10.1371/journal.pcbi.1007358
ISBN: ""
ISSN: 1553-7358
url: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007358
importance: "8"
status: complete
tags:
  - article
---

## Seven quick tips for analysis scripts in neuroimaging

### Table of Contents

- [Annotations](#annotations)

- [Notes](#notes)

+ [Commentaries](#commentaries)

- [Appendix](#appendix)

### Annotations




#### Page 2







> Of special interest isthe scripts folder of that repository, which contains the analysis scripts.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---






> *(No annotated text)*



**Comment**: The config file is an interesting concept. Add prefixes to scripts (e.g. 01_psd.m). Add descriptive prefixes for non-analysis scripts (e.g. figure_src.m)


- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> However, should you wish to construct apipeline similar to the example, astripped down version can be found at https://github.com/aaltoimaginglanguage/study_templatealong with instructions on how to use itas atemplate for new analysis pipelines.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Complexity perspective





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Thematic perspective





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Time perspective





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 3







> pipeline consists of 13 analysis scripts that process the data, five visualization scripts that construct the figures used in publications, aconfiguration file (config.py), and a"master" script that calls the individual analysis scripts (dodo.py, see Tip 3).





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---




![](<0 - Supplementary/images/vlietSevenQuickTips2020.md/image-3-x67-y396.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 5




![](<0 - Supplementary/images/vlietSevenQuickTips2020.md/image-5-x115-y476.png>)



> *(No annotated text)*




- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 6







> Programming acomputer isnot unlike receiving awish from amischievous genie: You will get exactly what you asked for but not necessarily what you wanted.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Therefore, an analysis pipeline should invite frequent visual checks on all intermediate results.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> The fifth tip isthat for each intermediate result, the script should create avisualization of the result and save itto disk.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> After running all the analysis scripts, acomplete visual record should be available of the data as itmoves through the pipeline. Care should be taken that the order of the figures matches that of the analysis steps.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Whenever an intermediate result issaved to disk in the example analysis pipeline, asimple visualization isalso created and added to a"report" file. The main analysis package used in the example pipeline, MNE-Python [27], provides areport class that compiles aset of figures into asingle HTML file.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Instead of copying the value of aparameter into all scripts that need it, the parameter should be imported, i.e., the programmer specifies the location where the parameter isdefined and the programming language will take care of fetching the value when itisneeded. In the programming literature, this isreferred to as the "don’t repeat yourself" (DRY) principle





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 7







> The example pipeline has acentral configuration script config.py, which defines all relevant parameters for the analysis, such as filter settings, the list of subjects, the experimental conditions, and so forth.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> Agood strategy isto alternate between bouts of creativity (where "technical debt" [29] isallowed to accumulate) and periods of cleaning up, during which the overall organization and design of the pipeline isreevaluated and the technical debt repaid.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page 8







> Deleted files were never truly gone though, as the project is managed by the VCS git [31, 32]. Git keeps track of the history of afile, allowing to





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---



#### Page undefined







> Papers have had to be retracted due to programmer error [8–10].





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> There isalarge body of literature on managing complexity and reducing the chance for programmer error in software [16–20]. However, most of itdeals with the construction of programs and software libraries intended to be used across projects.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---







> This makes scripts somewhat of an outlier in the software landscape, as they are pieces of code that are not reusable (pieces that need to be reusable are better implemented in asoftware library), only have to function correctly on one specific data set (hence there islittle need to test for "edge cases"), and will generally only be used by yourself and your collaborators (save the occasional run for review purposes and replication studies). Therefore, many of the standard practices of the software industry do not apply or need translation in order to arrive at concrete advice of what to do and what to avoid when writing analysis scripts.





- **Color**: #ffd400 (Yellow)
- **Date**: 2024-10-25 8:47 pm

---





### Notes



# Annotations  
(9/7/2024, 9:06:55 PM)

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=1&annotation=2U89J2H7) “Papers have had to be retracted due to programmer error [8–10].” ([Vliet, 2020, p. 1](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=1&annotation=ZL9JEK8C) “There isalarge body of literature on managing complexity and reducing the chance for programmer error in software [16–20]. However, most of itdeals with the construction of programs and software libraries intended to be used across projects.” ([Vliet, 2020, p. 1](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=1&annotation=8YR36ES9) “This makes scripts somewhat of an outlier in the software landscape, as they are pieces of code that are not reusable (pieces that need to be reusable are better implemented in asoftware library), only have to function correctly on one specific data set (hence there islittle need to test for "edge cases"), and will generally only be used by yourself and your collaborators (save the occasional run for review purposes and replication studies). Therefore, many of the standard practices of the software industry do not apply or need translation in order to arrive at concrete advice of what to do and what to avoid when writing analysis scripts.” ([Vliet, 2020, p. 1](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=2&annotation=B7QXXBED) “Of special interest isthe scripts folder of that repository, which contains the analysis scripts.” ([Vliet, 2020, p. 2](zotero://select/library/items/XFD5CLKE))

([Vliet, 2020, p. 2](zotero://select/library/items/XFD5CLKE)) The config file is an interesting concept. Add prefixes to scripts (e.g. 01_psd.m). Add descriptive prefixes for non-analysis scripts (e.g. figure_src.m)

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=2&annotation=S9W5FBTR) “However, should you wish to construct apipeline similar to the example, astripped down version can be found at https://github.com/aaltoimaginglanguage/study_templatealong with instructions on how to use itas atemplate for new analysis pipelines.” ([Vliet, 2020, p. 2](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=2&annotation=URAKUY3S) “Complexity perspective” ([Vliet, 2020, p. 2](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=2&annotation=LA3GSXUL) “Thematic perspective” ([Vliet, 2020, p. 2](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=2&annotation=2YMTG4FV) “Time perspective” ([Vliet, 2020, p. 2](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=3&annotation=I2R3LLU8) “pipeline consists of 13 analysis scripts that process the data, five visualization scripts that construct the figures used in publications, aconfiguration file (config.py), and a"master" script that calls the individual analysis scripts (dodo.py, see Tip 3).” ([Vliet, 2020, p. 3](zotero://select/library/items/XFD5CLKE))

  
[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=3&annotation=YJ7XDX9M)  
([Vliet, 2020, p. 3](zotero://select/library/items/XFD5CLKE))

  
[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=5&annotation=JXN47CZ3)  
([Vliet, 2020, p. 5](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=6&annotation=K29RYFEH) “Programming acomputer isnot unlike receiving awish from amischievous genie: You will get exactly what you asked for but not necessarily what you wanted.” ([Vliet, 2020, p. 6](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=6&annotation=YSQKGPHT) “Therefore, an analysis pipeline should invite frequent visual checks on all intermediate results.” ([Vliet, 2020, p. 6](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=6&annotation=U6XEJ7N7) “The fifth tip isthat for each intermediate result, the script should create avisualization of the result and save itto disk.” ([Vliet, 2020, p. 6](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=6&annotation=ISU74AIL) “After running all the analysis scripts, acomplete visual record should be available of the data as itmoves through the pipeline. Care should be taken that the order of the figures matches that of the analysis steps.” ([Vliet, 2020, p. 6](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=6&annotation=CRB84B6G) “Whenever an intermediate result issaved to disk in the example analysis pipeline, asimple visualization isalso created and added to a"report" file. The main analysis package used in the example pipeline, MNE-Python [27], provides areport class that compiles aset of figures into asingle HTML file.” ([Vliet, 2020, p. 6](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=6&annotation=7KCFRFWG) “Instead of copying the value of aparameter into all scripts that need it, the parameter should be imported, i.e., the programmer specifies the location where the parameter isdefined and the programming language will take care of fetching the value when itisneeded. In the programming literature, this isreferred to as the "don’t repeat yourself" (DRY) principle” ([Vliet, 2020, p. 6](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=7&annotation=N4QC76BC) “The example pipeline has acentral configuration script config.py, which defines all relevant parameters for the analysis, such as filter settings, the list of subjects, the experimental conditions, and so forth.” ([Vliet, 2020, p. 7](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=7&annotation=PD6ZF7F5) “Agood strategy isto alternate between bouts of creativity (where "technical debt" [29] isallowed to accumulate) and periods of cleaning up, during which the overall organization and design of the pipeline isreevaluated and the technical debt repaid.” ([Vliet, 2020, p. 7](zotero://select/library/items/XFD5CLKE))

[Go to annotation](zotero://open-pdf/library/items/FEUCDU36?page=8&annotation=VYF35XJ6) “Deleted files were never truly gone though, as the project is managed by the VCS git [31, 32]. Git keeps track of the history of afile, allowing to” ([Vliet, 2020, p. 8](zotero://select/library/items/XFD5CLKE))

---



%% begin notes %%

### Bookmark

- **Bookmark**: Page <!-- Specify the page number or section -->
- **Status**: #complete 
- **Relevance**: 8
## Commentaries



%% end notes %%

## Appendix

### Authors


- [[Marijn van Vliet]] (author)




### Formatted Bibliography

Vliet, M. van. (2020). Seven quick tips for analysis scripts in neuroimaging. _PLOS Computational Biology_, _16_(3), e1007358. [https://doi.org/10.1371/journal.pcbi.1007358](https://doi.org/10.1371/journal.pcbi.1007358)


### Tags


- #magnetoencephalography

- #data_processing

- #neuroimaging

- #computer_software

- #creativity

- #data_visualization

- #habits

- #vision




### Attachments


- **Full Text PDF**: C:\Users\joaop\Zotero\storage\3RSPRTXG\Vliet - 2020 - Seven quick tips for analysis scripts in neuroimag.pdf




### Collections


- methodology

- masters-thesis





### Backlinking


#### Metadata Links


- publicationTitle: [[PLOS Computational Biology]]




- date: [[2020]]





<!-- Any additional notes or comments -->


%% Import Date: 2024-10-26T13:10:36.280+01:00 %%
