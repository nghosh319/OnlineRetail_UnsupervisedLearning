1. The unzipped folder name is - AIT580_Team2_Ghosh_Sonparote_sys
2. It consist of following files
	2.1 Online Retail Project.Rmd - The main project file with R Markdown code
        2.2 Online-Retail-Project.html  - HTML file with result of the above code in Rmd file
	2.3 OnlineRetail.csv - Input csv file
	2.4 README.txt - Instructions file
3. Place files 2.1, 2.2 and 2.3 at the same location in your system
4. Open R Studio and browse the above Rmd file from your system.
5. Change the path of the csv file in the code on line #29 as per the path in your system.
    Current path in the code : C:/Users/naray/OneDrive/Desktop/R-project/OnlineRetail.csv 
5. Run the code with Knit-> HTML to generate the HTML file again. Although the HTML file is attached in the zip file.
6. Alternatively the output is generated with all plots in the HTML file, can be referred directly without above steps.

Note: Please install the library mentioned in the code so that there is no error while running the markdown file.

Library to be installed and imported as follows:

library(rmarkdown)
library(DT)
library(ggplot2)
library(tidyverse)
library(grid)
library(knitr)
library(dplyr)
library(lubridate)
#require(devtools)
#install_github("Displayr/flipTime")
library(flipTime)
library(factoextra)
library(gridExtra)
library(fpc)
library(tidyr)
library(cluster)
library(clValid)
library(dendextend)
