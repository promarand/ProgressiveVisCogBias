# Impact of Cognitive Biases on Progressive Visualization
Data and analysis scripts for TVCG paper "Impact of Cognitive Biases on Progressive Visualization"

This is a clone of the data found on IEEE DataPort: https://ieee-dataport.org/open-access/impact-cognitive-biases-progressive-visualization

## Instructions
Run the provided .Rmd script in RStudio. Data files must be in the same directory as the .Rmd script. Knitting this file will result in an HTML document with figures saved as .pdfs


### Download and install R 
https://cran.r-project.org/mirrors.html

(Last tested with R-4.0.3 for Windows (32/64 bit) and installed with all default options).

### Download and install R Studio Desktop (free)
https://rstudio.com/products/rstudio/download/

(This script last tested with verison RStudio Desktop 1.4.1103 and installed with all default options).

### Open RStudio
RStudio may request permission to update and install packages. Select Yes if prompted.

### Open installPackagesScript.r and run all lines to install necessary packages:
Select all lines and click "run" (or use ctrl+shift+s to run all lines).

### Open ProgVisBiasAnalysis.Rmd
There may be a notice banner of missing packages at the top of the file. "installPackagesScript.r" should have installed all necessary packages but if there are others, click "install" on the banner to install any outstanding packages.

### Run Script
Next, "knit" the file to execute all the code and generate images and statistics. This will save all images in teh folder the .rmd file resides.
Click File--> Knit Document.

This may take a minute or so but you can see the progress in the console window.  When completed, a new window will open showing the resulting HTML file and all figures will be saved to the same directory as the scripts.
