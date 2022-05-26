# r_workshop_2022_05_27_dataframes
Axel Nohturfft  
St. George's University of London  
27-May-2022. 


## Topics covered  

1. Creating, reading and writing (saving) data frames  
2. Viewing, inspecting and summarising data frames  
3. The "tidy data" concept  
4. Editing and reshaping data frames  
5. Subsetting (filtering) and cleaning data  

## Preparation for the workshop  

### Expected background knowledge  

1. This will be a beginners/improvers workshop that builds on a [previous beginners workshop](https://github.com/nohturfft/r_workshop_2019_11_29) held in April. You are strongly encouraged to briefly review the material covered during the previous workshop.  
2. We will be working with scripts written in [Rmarkdown](https://rmarkdown.rstudio.com/); you might find it useful to familiarise yourself with this format if you haven't used it before. Consider downloading the [Rmarkdown cheat sheet](https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) as a handy reference.  

### Installing R and RStudio  

If you haven't already done so, [install first R](https://www.r-project.org/), then [RStudio](https://rstudio.com/products/rstudio/download/) on your computer. That way you can try out the code we'll cover during the practice breaks. Of course, you may choose to just follow the presentation.  

### Accessing R/Rstudio Server  

If you prefer to access RStudio Server online, please go to [https://stats3.sgul.ac.uk/rstudio/](https://stats3.sgul.ac.uk/rstudio/).  
Note that you will need a good amount of disk space allowance for your H drive.  
If you are offsite, you might need to first connect to [mydesktop](mydesktop.sgul.ac.uk).  


### Install packages  

We will be using a number of different R packages.  
Please install these by running the following code from the command prompt:  

```
if (!require(magrittr)) install.packages("magrittr")
if (!require(readr)) install.packages("readr")
if (!require(readxl)) install.packages("readxl")
if (!require(lubridate)) install.packages("lubridate")
if (!require(ggplot2)) install.packages("ggplot2")
if (!require(DT)) install.packages("DT")
if (!require(knitr)) install.packages("knitr")
if (!require(rmarkdown)) install.packages("rmarkdown")
```

Alternatively, you can install packages using the RStudio `Tools > Install Packages...` menu.  

### To create a copy of this repository in RStudio follow these steps:  

1. Start RStudio  
2. File menu > New project...  
3. Choose: Version Control > Git  
4. Paste the following address into the "Repository URL" field: https://github.com/nohturfft/r_workshop_2022_05_27_dataframes  
5. Press tab key ("Project directory name" field will be filled automatically)  
6. Choose a desired folder in the "Create project as subdirectory of..." field  
7. Click the "Create project" button  
8. Open the first script ...

