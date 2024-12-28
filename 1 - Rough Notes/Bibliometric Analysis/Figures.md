# Editing
+ Power-Point
+ Inkscape
+ Adobe 
+ Paint
Mostly for cropping.
# Export
It is very important to ensure you are exporting high-quality figures into your papers. Here are a few tips to ensure that.
## Export from Power-Point
Always work with a high-resolution screen. It is known that screenshot quality is dependent on screen resolution [source](https://answers.microsoft.com/en-us/windows/forum/all/sharper-screenshots/46a1bc8c-ca80-46e4-ba32-9606cb7b0510). 
+ PPI (pixels per inch)
Power-point exports images with 96 PPI by default. This can be changed by following the steps detailed in [here](https://learn.microsoft.com/en-us/office/troubleshoot/powerpoint/change-export-slide-resolution). To check the PPI of any image, open it using paint and hit `Ctrl+E`. The PPI value is detailed in the `Resolution` field.
### Removing Transparent Background
When you are editing in Powerpoint, it is likely that the exported png file has transparent parts. When adding the figure to Latex, the figures will be added automatic borders or outlines. One quick solution is simply to use the jpg format; however, data quality might be lost. 
The best way to avoid this problem is to use GIMP, a software tool for image manipulation. Simply open the image in GIMP, right-click it and remove the alpha channel. Then simply export back as png.