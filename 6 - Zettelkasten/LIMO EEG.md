---
creation date: 2024-11-23 01:17
aliases:
  - LIMO
  - Hierarchical Linear Modeling
tags:
  - baby
modification date: Saturday, 23rd November 2024, 01:17:56
id:
---
---

## Parent note
---
## Backlinking
[[pernetLIMOEEGToolbox2011]]

---
# LIMO EEG
The main goal of the toolbox is to provide ‘full space’ analyses of experimental effects, i.e. simultaneously for all time and/or frequency time points and all channels, independent components or sources ([Getting started with LIMO MEEG - FieldTrip toolbox](https://www.fieldtriptoolbox.org/getting_started/limo/)).
>[!figure] ![[Pasted image 20241201015008.png]]
>*Figure 1*: Workings of [[LIMO EEG|LIMO]].

---
# Notes
## Usage
*To use LIMO you must:*
1. Import your BIDS-formatted dataset into [[EEGLAB]] using `pop_importbids`, which is a function from a plugin.
2. You must then precompute measurements such as the [[ERP]], ERSP, and PSD.
3. Create a study design.
4. Compute EEG features and specify parameters.
5. Choose statistical method.
6. View results by always loading the channel location `.mat` file (see [[General Linear Modeling of EEG in EEGLABLIMO part 2 Practicum - YouTube]])
## Troubleshooting
If the toolbox cannot find the derivatives folder, create it manually.
## Definition

## Associations
Variable specifications can be found [here](https://github.com/LIMO-EEG-Toolbox/limo_tools/wiki/information-and-dimensions-about-files-on-drive).
## Interpretation

---
## Links
- [Google Search](https://www.google.com/search?q=LIMO+EEG)

---
# Bibliography
+ 