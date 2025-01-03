## Programming Languages

Some programming languages fit neuroscientific research better than others.
- [[R]]
- [[MATLAB]]
- [[Python]]

![Graphical user interface, application, chat or text message  Description automatically generated](<2 - Source Material/Masters/attachments/Graphical user interface application chat or text message  Description automatically generated.png>)

Figure 174. Features of a sample of commonly used programming languages. C/C++ is by far the fastest language, as it is lower level (and thus conceptually more difficult), compiled and closed to the machine language. MATLAB and Python are conceptually similar at first, but Python is faster, does not come with a hefty price tag, and provides for higher concept usability. Igor can be useful as an out-of-the-box program for entry-level neuroscience but is difficult to adapt to specific needs. Excel is great for basic cut-and-paste plots, but its performance does not scale, has limited reproducibility, and a modest price tag. Julia, a relatively young language, offers performance faster than Python, but lacks the diverse packages and ecosystem that has evolved around Python.

### Companies and Software

- EGI/Magstim
- Net Station Acquisition
- Net Station Review
- Net Station Tools
- BrainProducts
- BrainVision

The BrainVision data format consists of three separate files:

- A text header file (.vhdr) containing meta data.
- A text marker file (.vmrk) containing information about events in the data
- A binary data file (.eeg) containing the voltage values of the EEG

Both text files are based on the Microsoft Windows INI format consisting of:

- sections marked as **[square brackets]**
- comments marked as **; comment**
- key-value pairs marked as **key=value**

### Packages

- EEGLAB