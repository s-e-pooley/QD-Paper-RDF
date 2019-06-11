# Radial-Distribution

Summary of work done on radial distribution scaling project: 
  
  1. AFM scans were performed on each sample being used to produce RDS plots. 5 x 5 um, 2 x 2 um, and  1 x 1 um scans were taken of each sample, where all but one sample exclusively utilized a 2 x 2 um scan. Many scans (taken from different locations on the sample) had to be used to produce the RDS plot for 1 one sample. 
  2. Imagej was used to determine the x and y coordinates for each quantum dot (QD). Imagej has a feature that allows the user to drag a bar across an image, with the idea that the distance being convered is known. Distances across each scan were known considering that the scan size of each image were known. A horizontal bar was made that stretched arcoss the entire image. A known distance was entered into imagej which had a known distance of the bar in pixals. Imagej correlated the distance of the bar in pixals to the distance and units that the user entered. For all scans, the units utilized were micrometers. After the known distance was entered, a mouse cursor was positioned, as close as possible, to the center of each QD. Imagej displayed the x and y coordinates at the top of the image. 
  3. All x and y coordinates were entered into a Microsoft Excel sheet, with the x coordinates being entered in the A column, y coordinates in the B column, and z coordinates in the C column. All coordinates are in units of micrometers. Multiple excel files have many different sheets located at the bottom of each file. These sheets represent coordinates taken different scans. All sheets have the RDS performed on their coordinates which are then averaged with every other sheets' coordinates to produce the RDS plot for that particular sample. If enough data points were acquired off of one image, then only one sheet will be found. 
  4. The excel sheets were then uploaded (previous method) onto the codelab.boisestate.edu website for the RDS code to compute. A "for" loop can be found within the program which was used to iterate through each sheet in the excel file to produce an RDS plot for the sample in question. The bin size was adjusted by changing the numerical value associated with "dr," with the units of "dr" being micrometers. An rmax value was used to tell the program the maximum radius to compute the RDS up to; the units of rmax are micrometers. 
  
  
