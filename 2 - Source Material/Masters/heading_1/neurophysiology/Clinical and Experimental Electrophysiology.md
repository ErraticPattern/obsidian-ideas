## Clinical and Experimental Electrophysiology

The purpose of clinical electrophysiology is to utilize diagnostic devices used in neurological settings, in order to ascertain the correct function of the peripheral and central nervous system, by making use of the electrical properties of the nervous tissue and with clinical goals.

### The Neuronal Electrical Signal

See _Niedermeyer’s Electroencephalography: Basic Principles, Clinical Applications, and Related Fields, 7 ([[#^comment-0|Comment Unknown Author 1]]) ed., p. 42-59, p. 129_.

The dipole theory is a mathematical simplification that allows to better understand the electrical dynamics of the neuron. A dipole is a separation of charges over a distance, which can be recorded using electrodes (e.g., EEG), and whose direction goes from the positive to the negative charge. The dipole creates an electrical field perpendicular to the cortex. The dipole is also created in an AP. **Current source density (CSD)** analysis corresponds to the net current entering or leaving the extracellular space; in this way it gives an estimate of the location of sinks and sources.

![](<2 - Source Material/Masters/attachments/Attachment 69.png>)

Figure 82. Formation of a dipole in pyramidal cells of the cortex. On the left, there is the formation of a EPSP, which makes the extracellular medium closer to the surface more positively charged, and on the right, there is a IPSP in the neuron, causing a negative charge closer to the surface. This is the principle of EEG signals.

Pyramidal cells are thought to be the main sources of the electrical activity recorded at the scalp. This is due to two main reasons: The first is that these neurons are present in the cortex which is closer to the recording electrodes than deeper brain regions and the second, perhaps most important reason is that the morphology of these neurons make them behave as if electrical dipoles, which makes the synchronous firing of thousands of these neurons (arranged in columns) a visible event in the EEG.

### Signal Acquisition and Processing

See _Niedermeyer’s Electroencephalography: Basic Principles, Clinical Applications, and Related Fields, 7 ([[#^comment-0|Comment Unknown Author 1]]) ed., p. 224_.

Signals can either be patterned or stochastic. The former is the desired signal to be acquired, since it represents non-random biological information, and the latter is desired to be filtered.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 7.png>)

Figure 83. Important steps in acquiring biological electrical potentials.

Electrical signals are acquired by devices whose underlying principle is that of the galvanometer. The galvanometer measures differences of electrical potential (voltage) between two electrodes – the red and black poles. The black pole is usually the reference pole (value of 0 volts).

![](<2 - Source Material/Masters/attachments/Attachment 70.png>)

Figure 84. An old (left) and recent (right) galvanometer, with the respective circuit representations.

#### Electrodes

These convert biological ionic potentials into electrical potentials. They are usually made out of metals which allow for good electrical conduction.

#### Input Protection

Protection against the input is necessary for the protection of the device and its user by implementing various techniques such as galvanic isolation.

#### Amplifier

Amplifies the signal since most biological signals are small in amplitude. A differential amplifier amplifies the electric potential between the two electrodes. Most amplifiers have built-in high-pass filters that attenuate very slow fluctuations because they may cause **amplifier saturations**. ([[#^footnote-14|Comment Unknown Author 14]]) However, there are DC-coupled amplifiers that are suitable for recording fluctuations below 1 Hz.

![Details are in the caption following the image](<2 - Source Material/Masters/attachments/Details are in the caption following the image.jpeg>)

Figure 85. Schematic representation of the EEG amplifier.

#### Filters

High-pass filters let the high frequencies pass. Low-pass filters do the opposite. Band-pass filters cut both high and low frequencies. [[Band-stop filter]]s cut a select region of frequencies – in Portugal these are used to cut the 50 Hz frequencies of emanating AC.

Filter capacity can be assessed with measures such as **signal-to-noise ratio (S/R)** and **Common Mode Rejection Ratio (CMRR)**. CMMR is used in differential amplifiers since these record the difference in voltage between the two electrodes. A high CMRR value indicates that the differential amplifier can effectively reject common mode signals ([[#^footnote-15|Comment Unknown Author 15]]), while a low CMRR value indicates that the common mode signals are being amplified along with the differential signal, which can lead to errors or inaccuracies in the output signal.

See also -> [[Analogue to Digital Converter]]

#### Signal processing

Techniques include the FFT and the Wavelet transform.

### Small Fiber Neurophysiology (SFN)

Standard electrophysiological tests cannot detect abnormalities of nerve fibers less than 7–10 m in diameter. Thus, normal electromyography and nerve conduction test results do not rule out SFN. Some specific tests for SFN include:

**Pain-related EPs using laser (LEP)** stimulation which allows for objective functional assessment of small fibers. Laser stimuli selectively excite Aδ and C mechano-thermal nociceptors in the hairy skin and evoke brain potentials. Aδ result in late laser evoked potentials (LEPs) constituted by a widespread N2±P2 complex of maximum amplitude at the vertex. Ultralate LEPs reflect the activity of the unmyelinated nociceptive pathway – C fibers.

**Quantitative sensory testing (QST)** uses precisely graded and reproducible stimuli to estimate sensory and nociceptive thresholds. Is a powerful method to follow-up somatosensory disturbances of various modalities – sensitivity of 60%- 85% -, but it is widely subjective. Heat pain QST assesses C fiber physiology, while cooling QST assesses Aδ; vibration tests assess Aα and Aβ nerve fibers.

SFNs related to autonomic function are usually assessed in sudomotor and cardiac functions. **Sympathetic skin response (SSR)** is assessed by inducing skin galvanic reflexes and are associated with non-myelinated fibers.

Quantitative sudomotor axon reflex testing (QSART)evaluates sympathetic response, but it is challenging to perform. Sudoscan is a new innovation that is much easier perform.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 1.jpeg>)

Figure 86. The sudomotor axon reflex. Ten% acetylcholine applied through iontophoresis (shown with the black arrows) bind to muscarinic receptors causing local sweat production (dashed arrows). The action potential travels antidromically and then it reaches nerve branching sites, anterograde propagation reaches to neighboring eccrine sweat gland and induce indirect sweat response (dotted arrows)(Suh, 2022).

### Electroencephalography (EEG)

Electroencephalograms (EEGs) consist of recording of the spontaneous electrical activity generated by active neurons in the brain, mainly the cortex. In general, the brain produces electrical activity divided into two parts – simultaneous rhythmic components, often called brain waves, and event related potentials, related to sensory stimulation or task-related thinking (Furth & Ph, 2018).

![Graphical user interface  Description automatically generated](<2 - Source Material/Masters/attachments/Graphical user interface  Description automatically generated.png>)

Figure 87. EEG temporal and spatial resolution.

EEG mainly records the activity of pyramidal cells of the cortex (layers VI, V, IV, III/II) (Thomson et al., 2007). The EEG does not record APs, but it records fPSPs, either excitatory or inhibitory. A single PSP is not strong enough to be registered by the EEG but fPSPs generate a dipole which is strong enough to be registered by the EEG. The temporal summation of several PSPs, which reflects the synchronous activity of the cortex, contributes to the intensity of the signal to be picked up by the EEG; in fact, it is necessary **that there be at least 6cm ([[#^comment-0|Comment Unknown Author 2]]) of synchronous activity for there to be a signal.** The orientation of the neurons and of the fPSP also contribute to signal intensity. If the orientation of EPSPs and IPSPs overlap, then there is charge neutralisation and the signal will be weaker. Finally, the tissues which the signal must transverse, such as fat, skin, bone, CSF, and muscle, modulate the signal itself. To measure deep brain activity from the scalp, those deep brain sources must produce powerful fields, and there should be many trials for averaging. For example, studies on brainstem-generated potentials generally have thousands of trials to obtain sufficient signal-to-noise. The second reason why activity from deep brain structures is difficult to measure from the scalp is that populations of neurons in subcortical structures are not often arranged in a geometrically parallel orientation - leading to a cancellation of potentials.

The temporal resolution of EEG is determined by the sampling rate of the acquisition. It is generally between hundreds and a few thousands of samples per second. The temporal precision, in contrast, depends on the analysis applied. temporal accuracy is extremely high because brain electrical activity travels instantaneously (within measurement possibilities) from the neurons generating the electrical field to the electrodes that are measuring those fields.

![Shape, circle  Description automatically generated](<2 - Source Material/Masters/attachments/Shape circle  Description automatically generated.png>)

Figure 88. Bull’s-eye illustration of the differences among resolution (R), precision (P), and accuracy (A). Up-and down arrows indicate high and low levels. Resolution is illustrated by the number of dots, precision is illustrated by the spread of the dots, and accuracy is illustrated by the distance of the dots away from the center of the bull’s-eye.

Although EEG has high temporal precision, resolution, and accuracy, its spatial precision, resolution, and accuracy are all relatively low compared to high-spatial-resolution imaging techniques such as fMRI. The spatial resolution of EEG is determined by the number of electrodes. The spatial precision of EEG is fairly low but can be improved by spatial filters such as the surface Laplacian or adaptive source-space-imaging techniques. The spatial accuracy of EEG is low. Activity recorded from one electrode does not reflect only activity from neurons directly below that electrode, but rather, from a complex mixture of activities from many brain regions close to and distant from that electrode.

Lastly, the signals captured by the EEG reflect meso- and macroscopic scales, but not microscopic scales which involve individual neurons or columns of neurons.

![](<2 - Source Material/Masters/attachments/Attachment 71.png>)

Figure 89. Orientation of the signal influences the amplitude captured in the EEG. Negative values are the result of the electromagnetic field imposed by the dipole in which there is electronegativity closer to the electrode (fEPSPs).

#### History of EEG

Larger waves of the first order with an average duration of 90 ms, and smaller waves of the second order with an average duration of 35 ms with the larger waves having deflections of 0,00015—0,0002 Volt at most. Although, in his second report, Berger named the larger waves “**alpha-waves**” and the smaller waves “**beta-waves**”.

Berger mentions some preliminary experiments on his son Klaus that led him to the idea that intense mental effort and focused attention induce a predominance of the smaller and shorter waves, which is now referred to as alpha blocking (Herrmann et al., 2016).

#### EEG “Hardware”

See also -> [[Electrode Placement Systems]]
See also -> [[Reference Systems]]
See also -> [[Electrodes]]

#### Setup for EEG experiments

Because the electrical conductivity of air is almost zero, a physical electrical bridge must be formed between the skin of the scalps and the EEG electrodes which is why scalp EEG electrodes require electroconductive gel, paste, or salt-water-soaked sponges.

Event markers, or triggers, are square-wave pulses that are sent from the stimulus- delivering computer to the EEG amplifier and are usually recorded as a separate channel in the raw data file (or sometimes, multiple channels).

![Text  Description automatically generated](<2 - Source Material/Masters/attachments/Text  Description automatically generated.png>)

Figure 97. Example EEG data showing 3 s of data and three experiment markers. The experiment markers are represented as vertical lines, and the numbers on top of the vertical lines correspond to particular events. In this case the numbers 3 and 5 refer to two response buttons being pressed by the subject, and the number 107 corresponds to a particular stimulus. This picture was made using the eeglab lab function eegplot.

See also -> [[EEG Tasks]]

#### Frequencies

Brain rhythms are grouped into bands that are defined by logarithmically increasing center frequencies and frequency widths. Brain rhythm frequency bands include delta (2 – 4 Hz), theta (4 – 8 Hz), alpha (8 – 12 Hz), beta (15 – 30 Hz), lower gamma (30 – 80 Hz), and upper gamma (80 – 150 Hz). These are not the only frequency bands; there are oscillations in the subdelta and omega (up to 600 Hz) ranges, but the frequency bands that are most typically associated with cognitive processes in the literature are between 2 Hz and 150 Hz. ([[#^footnote-17|Comment Unknown Author 17]]) However, there are no precise boundaries defining the bands. You might see theta referred to as 3 – 9 Hz or 3 – 7 Hz or 4 – 7 Hz. Furthermore, individual differences in peak frequencies have been linked to a number of individual characteristics, including brain structure, age, working memory capacity, and brain chemistry.

These oscillations are thought to be created by the interaction between pyramidal neurons and interneurons, which result in periodic states of maximum activation and inhibition. There are, however, other factors that modulate oscillation’s characteristics. See the book _Rhythms of the Brain_ by Buzsaki for more information.

![](<2 - Source Material/Masters/attachments/Attachment 73.png>)

Figure 98. Common frequencies observed in EEG (Mari-Acevedo et al., 2019).

Common frequency bands:
+ [[Gamma band]]
+ [[Alpha State]]
+ [[Beta Band]]
+ [[Mu rhythm]]
+ [[Theta band]]
+ [[Delta band]]

#### Cognitive electrophysiology

![A diagram of a brain activity  Description automatically generated](<2 - Source Material/Masters/attachments/A diagram of a brain activity  Description automatically generated.png>)

Figure 99. Different uses of EEG subfields.

The big question of cognitive electrophysiology is whether electric fields are casually related to cognition. Although there is no certainty in the answer, evidence has to believe the answer is yes. For example, studies have shown local field potentials (in this case, meaning the volume currents produced by a group of neurons) can influence the timing of action potentials. The synchronization between action potential timing and field potential phase has led to theories of **phase coding.** Other theories suggest that interregional oscillatory synchronization is a mechanism underlying the transmission of information across neural networks and that this synchronization- mediated connectivity is crucial for perceptual and cognitive processes. Finally, this question can be assessed by use of optogenetics and TACS (transcranial alternating-current stimulation) which are techniques capable of stimulating neurons at a certain frequency.

High-temporal-resolution techniques such as EEG are exceptional tools for studying neurocognitive processes.

- The first reason is that these methods capture **cognitive dynamics in the time frame in which cognition occurs**. Most cognitive processes occur within tens to hundreds of milliseconds. Furthermore, cognitive events occur in a temporal sequence that may span hundreds of milliseconds to a few seconds. ([[#^footnote-19|Comment Unknown Author 19]])
- The second reason is that EEG measurements **directly relate to neural activity** and although it is not fully known exactly what neurophysiological factors contribute in what proportion to the EEG signal that is measured from outside the head, it is generally not debated that EEG measures the meso- and macroscopic neural dynamics produced by populations of cortical neurons.
- Third, the EEG signal is **multidimensional**. EEG data comprise at least four dimensions: time, space, frequency, and power (the strength of frequency-band-specific activity) and phase (the timing of the activity; power and phase are discrete elements of a dimension because they provide largely independent information).

However, there are also questions where EEG data is not very useful.

- In general, EEG is not well suited for studies in which precise functional localization is important, and EEG is not well suited for testing hypotheses about deep brain structures. ([[#^footnote-20|Comment Unknown Author 20]])
- Questions concerning cognitive processes that are slow and that have an uncertain and variable time course. In fact, many EEG analyses become unreliable when the cross-trial jitters in timing are longer than a few tens or hundreds of milliseconds. ([[#^footnote-21|Comment Unknown Author 21]])

Since, as of now, there is no imaging technique in which each individual’s neurons activation state can be assessed, the current paradigm for explaining cognition and therefore all behaviour is that of frequencies. This field tries then to correlate every cognition with a specific frequency pattern. Can we say this is true of the C. _elegans_?

##### Interpretation of EEG data

The unit of measurement of EEG is **volts** (typically, microvolts or μV). Voltage values from an EEG study cannot be interpreted in an absolute sense since it varies depending on several factors.

- Microvolt values will change depending on data processing and analysis decisions, including the choice of reference and the time period used for baseline subtraction.
- Microvolt values differ across subjects according to factors that may be of no interest to cognitive electrophysiologists, including skull shape and thickness, scalp preparation during the recording, the orientation of the dipole in the brain that generated the scalp-measured activity, cortical folding, whether the subject washed his or her head that morning, and other factors such as the setup’s potential hardware problems. ([[#^footnote-22|Comment Unknown Author 22]])

Therefore, the voltage values can only be interpreted in a **relative manner**. This is not necessarily negative since it allows for the use of analysis that transform the original data. In fact, analyses that involve scale transformations (such as decibel normalization for time-frequency power data) offer an advantage over analyses that retain the original data scale: individual differences in raw values are eliminated, and thus the results can be more easily compared across electrodes, subjects, recording equipment, and publications.

Flattening of the signal could be due to the presence of a liquid, in which case it might indicate a subdural hematoma.

#### EEG data analysis

**Data analyses** have terms. Analysis terms are useful short-hand references for a set of assumptions and mathematical equations that are applied to data. For example, the terms “correlation,” “factor analysis,” and “general linear model” refer to specific data analysis procedures. Books that are denser with math and Matlab for advanced users and better explain the underlying theory of EEG data analysis’s tools include Chatfield, 2004, and van Drongelen, 2006. ([[#^footnote-23|Comment Unknown Author 23]])

Some form of baseline normalization is useful: baseline normalization removes or strongly attenuates patterns of activity that are present in the data but are unrelated to the task. Within task-related activity, a distinction can be made between phase-locked and non-phase-locked activity. Activity is **phase-locked** when its phase is the same or very similar on each trial, whereas activity is **nonphase-locked** when its phase is different on each trial, even if it is still time-locked to the trial.

Phase-locked activity (also sometimes called “ evoked ” ) is phase-aligned with the time = 0 event and will therefore be observed both in time-domain averaging (the ERP) and in time-frequency-domain averaging. Non-phase-locked activity (also sometimes called “ induced ” ) is time-locked but not phase-locked to the time = 0 event.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 8.png>)

Figure 100. Illustration of whether time-frequency (TF) power and the ERP can measure phase-locked, non-phase locked, time-locked, and non-time-locked activity. The left column of each cell shows four trials of simulated data, and the right column of each box shows the average of those four trials. Black lines show the raw time series, and gray lines show the time course of 10-Hz power. The ERP captures only phase-locked and time-locked activity. Time-frequency power can measure time-locked activity regardless of whether it is phase-locked or non-phase-locked. Activity that is not time-locked can be measured with time-frequency power, although the results will be smoothed and thus less temporally precise.

##### EEG preprocessing

Pre-processing refers to any transformations or reorganizations that occur between collecting the data and analysing the data. Some pre-processing steps merely organize the data to facilitate analyses without changing any of the data (e.g., extracting epochs from continuous data), other pre-processing steps involve removing bad or artifact-ridden data without changing clean data (e.g., removing bad electrodes or rejecting epochs with artifacts), and some pre-processing steps involve modifying otherwise clean data (e.g., applying temporal filters or spatial transformations).

_The goal of preprocessing can be stated succinctly: to apply those methods that maximize the significance of the data between conditions._

![A diagram of a process  Description automatically generated](<2 - Source Material/Masters/attachments/A diagram of a process  Description automatically generated.png>)

Figure 101. Pre-processing pipeline of EEG data using the EEGLAB package for MATLAB.

Time-frequency-based analyses and time-frequency decomposition.

The **estimated SNR** is a considerable part of preprocessing relating to estimates of how much of the signal is actually real or simply noise.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 9.png>)

Figure 102. Theoretical depiction of signal and noise in EEG data as a signal detection problem. Different preprocessing strategies lead to different balances between the amount of noise versus signal that is retained in data. At one extreme (dashed vertical line a), the data contain nearly no noise, but this comes at the expense of losing signal. At the other extreme (dashed vertical line c), nearly all of the signal in the data is retained, but this comes at the expense of keeping noise in the data as well. There is no optimal position to take in this theoretical function; it depends on the kinds of analyses you are performing, how many trials you have, and how tolerant your analyses are to noise.

**Epoching** needs to be relative to the time of the trials and also take into account the later processing of the data, such as that of filtering which produce artifacts of frequency power at the beginning and end of the epoch.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 10.png>)

Figure 103. Edge artifacts resulting from discontinuous breaks in the time series between trials can contaminate the results if there are insufficient **buffer zones** to allow those edge artifacts to subside. In this case the edge artifacts are easily identifiable, and it is also clear that those artifacts subside before the time window of interest (gray area). In general, edge artifacts will contaminate up to three cycles of activity, but this could be less or more depending on the magnitude of the edges.

If you are reanalyzing a dataset that has already been epoched and cannot be reepoched from the continuous data, and if you are concerned that the epochs are too short and the time-frequency results might be contaminated by edge artifacts, you can use a **“reflection” approach**, whereby the EEG data from each trial and electrode are reversed and put in the beginning and end of the trial. However, introducing buffer zones is a better approach.

![Diagram, schematic  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram schematic  Description automatically generated.png>)

Figure 104. Data reflection procedure. Data are reversed in time, concatenated to both ends of the real-data time series, analyses are performed, and then the reflected data are trimmed. This procedure attenuates edge artifacts and can be useful if the epochs are cut too short for planned analyses.

Averaged mastoids (the bone behind the ear) or earlobes are typical reference electrodes. These are good choices because the reference electrodes are close to the other electrodes but record less brain activity. The **referencing ([[#^footnote-24|Comment Unknown Author 24]])** is important because noise in the reference electrodes will turn into noise in the scalp electrodes. Note that the surface Laplacian is reference independent. For a large number of electrodes (>100), or if electrodes are placed on the neck and face, an average reference is often recommended.

![A picture containing text  Description automatically generated](<2 - Source Material/Masters/attachments/A picture containing text  Description automatically generated.png>)

Figure 105. The effect of different reference electrodes on the same data. Earlobes refers to the average of electrodes placed on the two earlobes. In many situations, using one of the scalp electrodes as the reference is suboptimal.

**Interpolation** is a process by which data from missing electrodes are estimated based on the activity and locations of other electrodes.

![A graph of a graph  Description automatically generated](<2 - Source Material/Masters/attachments/A graph of a graph  Description automatically generated.png>)

Figure 106. Topographical illustration of interpolation. Displayed is a smooth topographical landscape (analogous to a scalp-measured voltage) that is discretely sampled (black dots; analogous to electrodes). Interpolation involves estimating the activity at the white “electrode,” given the activities and distances of all other electrodes. This topography was generated with the Matlab peaks function.

##### Time-domain Analysis

Time-domain analysis includes any type of analysis in which the independent variable is time.

**Event related potentials (ERPs)** are simple and fast to compute and require few analysis assumptions or parameters. The second advantage of ERPs is their high temporal precision and accuracy. Additionally, there is a rich literature concerning ERPs. Another advantage of ERPs is related to the first advantage: because ERPs are fast to compute and easy to look at, they provide a quick and useful data quality check of single subject data.

Limitations of ERPs include the fact that there are many kinds of dynamics in EEG data that do not have a representation in the ERP. The second limitation of ERPs is that they provide limited opportunities for linking results to physiological mechanisms. This is because the neurophysiological mechanisms that produce ERPs are less well understood compared to the neurophysiological mechanisms that produce oscillations.

Proposed models that seek to explain the neurophysiological basis of ERPs include the additive, phase-reset and amplitude asymmetry or baseline shift models. ([[#^footnote-25|Comment Unknown Author 25]])

Useful utilities for ERPs include **“erpviewerx”**.

![A picture containing diagram  Description automatically generated](<2 - Source Material/Masters/attachments/A picture containing diagram  Description automatically generated.png>)

Figure 107. Single trials were simulated by creating a 6-Hz sine wave and adding a 10-Hz stimulus response and some noise. Simulated data showing how time-locked but not phase-locked activity (left column) is lost in ERP averaging (middle column) but is visible in band-specific power (right column). Each row in the left column shows a different trial, and each row in the middle and right columns shows averages from the first until the current trial.

The mathematical basis of an ERP is simple: sum the voltage at each time point over trials and then divide by the number of trials.

**Error-related negativity (ERN)**, sometimes referred to as the Ne, is a component of an event-related potential (ERP). ERPs are electrical activity in the brain as measured through electroencephalography (EEG) and time-locked to an external event (e.g., presentation of a visual stimulus) or a response (e.g. an error of commission). A robust ERN component is observed after errors are committed during various choice tasks, even when the participant is not explicitly aware of making the error (wiki).

Fractal-based dynamics (multi-scale dynamics) and micro-scale dynamics also belong to time-domain analysis.

##### Frequency-domain Analysis

Frequency-domain analysis includes any type of analysis in which the independent variable, usually represented in the abscise axis, is frequency.

EEG data contain rhythmic activity. Even in raw, unfiltered, unprocessed data you can see rhythmic activity. This rhythmic activity reflects neural **oscillations**, which are fluctuations in the excitability of populations of neurons. Frequency is the speed of the oscillation and has units of hertz (Hz), which refers to the number of cycles per second and is the reciprocal of time. Thus, 2 Hz means two cycles per second, 40 Hz means 40 cycles per second, and 0.1 Hz means one cycle every 10 s. Power is the amount of energy in a frequency band and is the squared amplitude of the **oscillation** - a rhythmic alternation of states. Phase is the position along the sine wave at any given time point and is measured in radians or degrees.

![A picture containing text, nail  Description automatically generated](<2 - Source Material/Masters/attachments/A picture containing text nail  Description automatically generated.png>)

Figure 108. The three dimensions that define oscillations: frequency, power, and phase.

Limitations of static spectral analysis include the fact that real brain EEG data is highly non-stationary, a feature which is hardly interpretable from a frequency spectrum. This is the main motivation behind time-frequency analysis.

##### Time-Frequency-domain Analysis

The first **advantage** is that many results from time-frequency-based analyses can be interpreted in terms of neurophysiological mechanisms of neural oscillations. Most importantly, this type of analysis takes more information out of the EEG data manifold than time-based analysis.

**Limitations** include the decrease of temporal precision resulting from time-frequency decomposition. ([[#^footnote-26|Comment Unknown Author 26]]) The other limitation is that there are few theories that link this analysis’s results with cognitive functions, limiting hypothesis-driven research.

In general, analysis parameters allow you to choose better precision in one domain (time or frequency) at the expense of poorer precision in the other domain. ([[#^footnote-27|Comment Unknown Author 27]]) These analyses work with concepts such as **synchrony** and **phase-locking**. Imagine time-frequency results as a three-dimensional (3-D) cube, with the dimensions being time, frequency, and space (space is measured by electrodes). The most common data feature to plot is power, but phase clustering, connectivity, and correlation with behavior are also possible.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 11.png>)

Figure 109. The data cube, containing information over time, frequency, and space, is difficult to view or conceptualize and therefore is sliced in different ways to illustrate 1-D or 2-D snapshots of the results.

Useful functions (or utilities) include **“tfviewerx”** which shows simultaneously the time-frequency plot from one electrode and the topographical map at a selected time-frequency point.

![Diagram  Description automatically generated with medium confidence](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated with medium confidence.png>)

Figure 110. Method for the study of phase synchrony (Varela et al., 2001).

See also -> [[EEG microstates]]
See also -> [[Global Field Power]]

#### ERPs Analysis

ERSP – event-related spectral potential.

See also -> [[ERP metrics]]

#### Biophysics of EEG and MEG

See _Niedermeyer’s Electroencephalography: Basic Principles, Clinical Applications, and Related Fields, 7 ([[#^comment-0|Comment Unknown Author 1]]) ed., p. 189_.

Sampling of electromagnetic brain signals at millisecond intervals is readily achieved by EEG and MEG and is limited only by the multichannel analog-to-digital conversion rate of the measurements. The main question of this section is: How does one go from neuronal sources to LFPs, and ultimately to the EEG/MEG?

See _Electric Fields of the Brain: The neurophysics of EEG, 2 ([[#^comment-0|Comment Unknown Author 1]]) ed., chapter1, p.34._

About 6 cm ([[#^comment-0|Comment Unknown Author 2]]) of cortical gyri tissue (containing about 600,000 minicolumns or 60 million neurons forming a dipole layer) must be synchronously active to produce recordable scalp potentials without averaging.

See _Electric Fields of the Brain: The neurophysics of EEG, 2 ([[#^comment-0|Comment Unknown Author 1]]) ed., p.114._

There are both local and global delays in the brain: local because of the resistive characteristics of the capacitor and global due to the finite speed of the action potential’s propagation. _Consciousness of an external event must then operate in the range of the hundreds of milliseconds._

_Static membrane charge produces no electric field in tissue at the macroscopic distances of interest in EEG_ – this is due to the shielding effect of medium charges.

EEG deals with fields of relatively low frequency. _When fields are as such, electric fields are uncoupled from magnetic fields._ Therefore, electric fields can be calculated as if magnetic fields don’t exist and calculate magnetic fields from current source distribution, while ignoring any explicit interaction with the electric field. This is a very important factor [low-frequency approximation] that simplifies calculations since we can now deal with quasi-static electric fields instead of full-on electromagnetic fields.

Additionally, while still governed by Maxwell’s laws, the neural medium still affects the electric fields in a manner that must be accounted for.

#### Electrical source imaging (ESI)

**Topographical localization** refers to identifying the electrodes that show the maximum effect under investigation. **Brain localization** refers to identifying the locations in the brain that generated the activity measured from the scalp and is the goal of ESI. Thus, the main difference between these two terms is that topographical localization is a description of an observation, whereas brain localization is an interpretation of a result that is supported by some combination of theory, previous research, and data analyses in combination with spatial filters.

There are several types of **spatial filters** that can attenuate spatial autocorrelation and thus improve topographical or brain localization. These spatial filters also make the data more appropriate for connectivity analyses.

See _Niedermeyer’s Electroencephalography: Basic Principles, Clinical Applications, and Related Fields, 7 ([[#^comment-0|Comment Unknown Author 1]]) ed., p. 2150_.

Electrical source imaging (ESI) is an emerging technique for reconstructing brain or cardiac electrical activity from electrical potentials measured away from the brain or heart. The concept of ESI is to improve on electroencephalography (EEG) or electrocardiography (ECG) by determining the locations of sources of current in the body from measurements of voltages ([Source](https://www.ncbi.nlm.nih.gov/books/NBK232494/#:~:text=Electrical%20source%20imaging%20\(ESI\)%20is,from%20the%20brain%20or%20heart.)).

In terms of source reconstruction accuracy, it is often said that **MEG is better for source localization than EEG**. In theory this is not true: with the same number of electrodes and highly anatomically accurate forward models, source reconstruction accuracy is similar for EEG and MEG and can be better with EEG for radial sources. In practice, however, it is often the case that source reconstruction accuracy is higher with MEG than with EEG. This is because most EEG setups have fewer electrodes compared to MEG sensors and because the precise positions of the EEG electrodes are rarely measured (instead, standard template locations are used). This decreases the accuracy of the forward model. Finally, the electrical conductances of the skull and scalp are difficult to measure and can be different for different individuals, and different across the skull for the same individual. ([[#^footnote-29|Comment Unknown Author 29]])

EEG has been ignored in regards its imaging potential and so the goal is to diminish this incorrect historical view and show that the EEG has considerably matured and can now be considered as a powerful, flexible, and affordable imaging technology, by way of ESI.

**EEG topographical mapping** refers to the bulk signal at any moment in time, across all of the scalp’s surface. EEG mapping is a precursor to source imaging, and the proper analysis and interpretation of EEG maps can give a great deal of information about the putative sources in the brain.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 12.png>)

Figure 112. Information flow and basic components of the forward and inverse problems (Zorzos et al., 2021).

The main problem of ESI is that of the inverse problem. The inverse problem can be stated as the inability to correctly deduce the true source for a given EEG signal since there are infinite solutions. Only by constraints can a solution be achieved.

See _Electric Fields of the Brain: The neurophysics of EEG, 2 ([[#^comment-0|Comment Unknown Author 1]]) ed., p.93._

For source imaging, we might choose each voxel to be 1 cm ([[#^comment-0|Comment Unknown Author 3]]) or N=1400 voxels for an entire brain. It is mathematically supported that unconstrained inverse solutions in EEG or MEG will remain forever intractable.

##### Case Study

![A picture containing text  Description automatically generated](<2 - Source Material/Masters/attachments/A picture containing text  Description automatically generated 1.png>)

Figure 113. Electrode names and two-dimensional topographical locations of EEG electrodes in the sample data provided with the book (see bibliography).

#### Finance of Neuroimaging

EEG setups can cost as much as fMRI or EMG ones (around 150,000$).

See also -> [[Neuroscience Databases]]

### Evoked Potentials (EPs)

Evoked potentials measure the electrophysiologic responses of the nervous system in response to a sensory stimuli. It has become less prevalent in clinical settings due to the power of imaging techniques such as MRI and are now used in conjunction with the former; in turn, EPs are useful to assess physiological functionality, particularly of known anatomical pathways. Since the amplitude of EPs are very small, it is necessary to employ averaging techniques. The measurement of EPs is given by the standardized system of either P – positive – or N – negative -, following a number denoting the time in milliseconds after the stimulus ([[#^footnote-30|Comment Unknown Author 30]]) (e.g., P100).

See also -> [[Somatosensory Evoked Potentials (SSEP)]]
See also -> [[Visual Evoked Potentials (VEPs)]]
See also -> [[Brainstem auditory evoked responses or potentials (BAER)]]

### Magnetoencephalography (MEG)

MEG can be used in conjunction with EEG because MEG is capable of detecting electric fields parallel to the scalp, contrary to EEG, since it records this electric field’s magnetic field, which is perpendicular to the former.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 14.png>)

Figure 118. Different schemes representing the underlying principle of EEG.

The unit of MEG is tesla (typically, femtotesla, fT, which is 10 ([[#^comment-0|Comment Unknown Author 15]]) tesla). MEG is better than EEG at detecting high-frequency activity (e.g., above 60 Hz). This is because magnetic fields pass through the skull and scalp, whereas the electrical fields are volume conducted through these tissues, which decreases signal-to-noise ratio at higher frequencies. It also is more sensitive to tangential dipole moments.

#### Magnetic Source Imaging

See _An Introduction to the Event-Related Potential Technique, 2nd edition, chapter 14._

The magnetic field passes unimpeded by the skull and therefore there is no need for tissue conductivity values for EMG localization, only the head model is required. Also, because it is orthogonal to the electric field, EMG gives complementary information to ESI.

Thus, magnetic signals are largest for superficial dipoles that run parallel to the surface of the skull and fall off rapidly as the dipoles become deeper and/or perpendicularly oriented, but voltages do not fall off rapidly in this manner. Since both fields have constraints, these can be used to reach the real solution. The main drawbacks of combining magnetic and electrical data compared to using magnetic data alone are that (a) a more complex head model is needed for the electrical data, and (b) some effort is required to ensure that the electrical and magnetic data are in exactly the same spatial reference frame.

![A diagram of a magnetic field  Description automatically generated](<2 - Source Material/Masters/attachments/A diagram of a magnetic field  Description automatically generated.png>)

Figure 119. Relationship between an electrical dipole and its associated magnetic field. An electrical dipole has a magnetic field running around it (A), and when the dipole is roughly parallel to the surface of the head, the magnetic field leaves and reenters the head (B). If the dipole is oriented radially with respect to the head, the magnetic field does not vary across the surface of the head (C). When a dipole runs parallel to the surface of the head (represented by the arrow in D), there is a broad region of positive voltage at the positive end (solid lines) and a broad region of negative voltage at the negative end (dashed lines), separated by a line of zero voltage (represented by the dotted line). The magnetic field, in contrast, consists of magnetic flux leaving the head on one side of the dipole (solid lines) and reentering the head on the other side (dashed lines), separated by a line of no net flux (dotted line).

### Transcranial Magnetic Stimulation (TMS)

It is a technique belonging to the broader group of **Non-Invasive Brain and Spinal Stimulation (NIBSS)**. In this group are also included: transcranial current stimulation (tCS) - which can be either continuous (tDCS) or slowly alternating in time (tACS) -, Transcutaneous spinal direct current stimulation (tsDCS), Transcutaneous spinal magnetic stimulation (tsMS) and TMS.

**TMS** consists in a strong and short-lasting current that flows through a coil located over the scalp, inducing a time varying magnetic field. This field will generate a time-varying electric field which will cause a suprathreshold current to act on the neuronal tissue. This current has the ability to cause APs in a painless way. The energy is given by AC, which then stored in a capacitor and then transferred to the coil.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 15.png>)

Figure 120. Illustration of direction of current flows in a magnetic coil and the induced current in the brain (from Hallett, 2007 – with permission). In magnetic stimulation, a brief, high-current pulse is produced in a coil of wire, called the magnetic coil. A magnetic field is produced with lines of flux perpendicular to the plane of the coil, which ordinarily is placed tangential to the scalp. The magnetic field can be up to about 2 T and typically lasts for about 100 ls. An electric field is induced perpendicularly to the magnetic field. The voltage of the field itself may excite neurons, but the induced currents are likely to be more important. In a homogeneous medium, spatial change of the electric field will cause current to flow in loops parallel to the plane of the coil, which will be predominantly tangential in the brain. The loops with the strongest current will be near the circumference of the coil itself. The current loops become weak near the center of the coil, and there is no current at the center itself. Neural elements are activated by the induced electric field by two mechanisms. If the field is parallel to the neural element, then the field will be most effective where the intensity changes as a function of distance. If the field is not completely parallel, activation will occur at bends in the neural element (Rossini et al., 2015).

The effects of TMS depend on the configuration of the coil(s), its distance from the tissue and the orientation of the neurons regarding the field ([[#^footnote-31|Comment Unknown Author 31]]). TMS stimulus intensity is determined by the individual’s **motor threshold (MT)** - defined as the minimal intensity of motor cortex stimulation required to elicit a reliable motor evoked potential (MEP) of minimal amplitude in the target muscle (Rossini et al., 2015).

![](<2 - Source Material/Masters/attachments/Attachment 75.png>)

Figure 121. Different configuration in TMS.

**Single-pulse TMS (spTMS)** can be used to diagnose the correct functioning of the corticospinal pathways. Stimulation of these pathways produces D-waves from the direct stimulation and I-waves which are repetitive responses in descending motor pathways, most likely related to interneurons, and are poorly understood. This technique can also be used to calculate the CMCT and PMCT, using the formula:

Another parameter which can be studied is the **Cortical Silent Period (CSP)**, in which following suprathreshold TMS in the motor cortex there is a period of no cortical activity. Finally, spTMS can be used to map the brain, in the same manner as other stimulation techniques.

![](<2 - Source Material/Masters/attachments/Attachment 76.png>)

Figure 122. Using spTMS to calculate the CMCT and PMCT.

**Paired pulse TMS (ppTMS)** allows assessment of intra-cortical inhibition and facilitation. It usually involves a conditioning stimulus (CS) followed by a test stimulus (TS), and the MEP amplitudes (usually peak-to-peak) or areas are compared to those produced by the TS alone as a reference (baseline/control) condition. Due to the trial-to-trial variability of MEP induced by TMS, at least 8–10 trials for each combination of CS/ TS intensities and interstimulus interval (ISI) between CS and TS should be tested. The studies are usually done with the target muscle at rest. Various types of facilitations and inhibitions can be analysed.

Repetitive TMS (rTMS) can either be high or low frequency, the former leading to excitation and the latter to inhibition. rTMS can be used to assess cognitive functions; it has been shown that using r-TMS impairs learning after performing some task, while it can enhance learning if applied before the task. It can also be used for epilepsy, in order to decrease cortical activity, strokes, in order to inhibit the healthy hemisphere, and depression.

![Diagram  Description automatically generated](<2 - Source Material/Masters/attachments/Diagram  Description automatically generated 16.png>)

Figure 123. Using EEG with TMG in order to create an open-loop system, and, in the future, a closed-loop system. Principal scenarios of brain stimulation with respect to the current brain state. (A) Standard NIBS approaches treat the brain as a static “black box” (left), disregarding its variable internal state and may hence result in highly variable stimulation effects. In contrast, treating the brain as the dynamic system it actually is (right) may reveal very different (state-dependent) effects, but each of them being more homogenous. (B) Open-loop brain state-independent brain stimulation neglects the current brain state; no neuroimaging method and no real-time system is necessary to control the stimulation. Open-loop brain state-dependent brain stimulation (BSDBS) uses concurrent neuroimaging (e.g., EEG) and real-time signal analysis to monitor the current brain state and to adjust and trigger brain stimulation accordingly, however, without systematically changing the monitored target brain state (e.g., TMS triggered by the amplitude or phase of a certain EEG oscillation to assess state-specific corticospinal excitability but without considerable effect on the monitored oscillation). Closed loop BSDBS additionally requires that the monitored brain state is actually changed by the stimulation, allowing to control the expression of a certain brain state (Bergmann, 2018).

It is important to understand the notion of membrane time constant. Neurons have time constants of around 5 - 20 milliseconds (ms), which means that after a neuron receives an input signal (or "spike") from another neuron, its synaptic potential’s voltage will jump up quickly and then decay to 37% above its resting state after 5 - 20 ms (depending on the exact time constant). Each type of neuron has a different time constant which can be checked [here](https://www.neuroelectro.org/ephys_prop/4/) ([source](https://www.quora.com/What-does-the-term-membrane-time-constant-mean-in-neuroscience)).

![Graphical user interface, text, application  Description automatically generated](<2 - Source Material/Masters/attachments/Graphical user interface text application  Description automatically generated 1.png>)

Figure 124. Types of pulses and contraindications of TMS.

See also -> [[EMG]]
See also -> [[Cortical Stimulation]]
See also -> [[DBS]]
See also -> [[Extracellular recordings]]
See also -> [[Patch-clamp]]
See also -> [[Voltage clamp]]
See also -> [[Current clamp]]