---
creation date: 2024-12-18 21:12
aliases:
  - fmri
  - FMRI
  - functional magnetic resonance
  - Functional magnetic resonance imaging
tags:
  - "#topic"
modification date: Wednesday, 18th December 2024, 21:12:47
---

## Parent note

## Functional MRI (fMRI)
Developed by [[Seiji Ogawa]] in 1990. The concept behind fMRI is that of measuring brain activity by measuring changes in blood flow. This can be achieved by the different magnetic properties of hemoglobin when bound to oxygen and when unbounded. This is due to the fact that oxygen surrounds the iron molecule and interferes with its attraction to the [[magnetic field]] created by the machine. The ratio between [[oxyhemoglobin]] and [[hemoglobin]] at any point determines the Blood Oxygenation Level Dependent (BOLD) signal, which represents 1 voxel (~3x3x3 mm).

![](<2 - Source Material/Masters/attachments/Attachment 17.png>)

According to the [[oxygenation hypothesis]], changes in oxygen usage in regional cerebral blood flow during cognitive or behavioral activity can be associated with the regional neurons as being directly related to the cognitive or behavioral tasks being attended. However, even though that the fMRI signal is linear on relation to brain activity, cognition is not linearly correlated with brain activity. Furthermore, since adjacent blood vessels also dilate in a specific activated area, there is less spatial resolution. Furthermore, temporal resolution is of ~3-5 seconds, which hinders any kind of inference about the type of brain activity (a train of smaller potentials or one big, evoked potential) represented in the fMRI signal. Furthermore, fMRI can be utilized to analyse functional connectivity in the brain.

![](<2 - Source Material/Masters/attachments/Attachment.jpeg>)

Figure 18. Examples of results from one fMRI study.

Functional MRI can be readily performed using a standard 1.5T clinical MRI magnet, although an increasing fraction of studies are now performed on higher field (3-4.5T) machines for improved SNR and resolution. fMRI studies are capable of producing spatial resolutions as high as 1-3 mm.

**TR** and **TE** are basic pulse sequence parameters and stand for repetition time and echo time respectively. They are typically measured in milliseconds (ms).

The echo time (TE) represents the time from the center of the RF-pulse to the center of the echo. For pulse sequences with multiple echoes between each RF pulse, several echo times may be defined and are commonly noted TE1, TE2, TE3, etc.

The repetition time (TR) is the length of time between corresponding consecutive points on a repeating series of pulses and echoes. The TR dictates how often a particular brain slice is excited and allowed to lose its magnetization. TRs could vary from the very short (500 ms) to the very long (3 s).

![Repetition Time (TR) and Echo Time (TE)](<2 - Source Material/Masters/attachments/Repetition Time (TR) and Echo Time (TE).gif>)

Figure 19. Basic components and nomenclature for fMRI data acquisition. GRE stands for gradient recalled echo.

Functional MRI has many different data types which must be explicated in the context of computational data analysis, especially in relation to the **BIDS convention**. The data types include:
1. _func_ (task based and resting state functional MRI)
2. _dwi_ (diffusion weighted imaging)
3. _fmap_ (field inhomogeneity mapping data such as field maps)
4. _anat_ (structural imaging such as T1, T2, PD, and so on)
5. _perf_ (perfusion)

## Links
- [Google Search](https://www.google.com/search?q=Functional+magnetic+resonance+imaging)

## Backlinking
+ 
## References
+ 