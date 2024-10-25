---
creation date: 2024-07-13 13:58
aliases:
  - common mode sense
  - driven right leg
tags:
  - "#adult"
modification date: Saturday, 13th July 2024, 13:58:21
id:
---
--- 
## Parent note
[[Alpha State]]---
## Backlinking


---
# CMS-DRL
The Biosemi system uses a common mode sense (CMS) and a driven right leg (DRL) electrode, which injects a small amount of current to improve the CMMR and minimize the effect of external noise sources. When recording data to disk and when reading it into FieldTrip, it is expressed as potential difference relative to the CMS. With this type of amplifier systems you should **always** reference after reading the data from disk, i.e. change the reference from CMS to another electrode, and you should **not** add the CMS electrode as implicit reference channel to the data. For channel-level analysis you may want to use linked mastoids, or linked T7 and T8. For source analysis you would (as with other systems) best reference to the average of all electrodes (minus CMS)([[#^3889c3]]).

---
# Notes


---
# Bibliography
+ [BioSemi EEG ECG EMG BSPM NEURO amplifiers systems](https://www.biosemi.com/faq/cms&drl.htm)
+ [Why should I use an average reference for EEG source reconstruction? - FieldTrip toolbox](https://www.fieldtriptoolbox.org/faq/why_should_i_use_an_average_reference_for_eeg_source_reconstruction/) ^3889c3