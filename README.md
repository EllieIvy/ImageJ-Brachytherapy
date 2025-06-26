# ImageJ-Brachytherapy
ImageJ analysis for HDR brachytherapy applicator QC

## 1. Line Source Analysis
A simple macro which provides a measurement of dead space and the locations of dwell positions along a straight line.

Input: Scanned autoradiograph of Flexitron source along a straight source path (TIF File)

Run the macro in ImageJ and select the image to be analysed.

Enter the scan resolution (dpi)

Draw a line along the source path, starting from the end of the applicator.  Accurate placement of the start of the line is important to ensure correct dead space calculation.

The program plots a line profile, smooths the profile and then calculates the positions of the maxima along the line.

A results table shows dead space and dwell position spacing.  
