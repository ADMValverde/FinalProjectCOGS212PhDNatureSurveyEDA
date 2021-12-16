# FinalProjectCOGS212PhDNatureSurveyEDA
Hello! This is a preliminary data analysis of the dataset used in this https://www.nature.com/articles/d41586-019-03459-7 article by nature. 

It is an analysis of a 2019 survey of PhD students.

I partially clean the data set and set up a work flow to finish cleaning and analyzing the data.

I also note some issues in the data and track the history of the data.

To run this, you must have R and R studio installed. When you download the zip file, begin by openning the file called "FinalProjectCOGS212PhDNatureSurveyEDA.Rproj".

Open that file with R studio, not R. Once it is opened, click on files, then on "CoreCode.Rmd", then click the upper righthand "run" section's drop down menu, 
and then click "run all". 

If that does not work, copy and paste the following into the empty space above "## Abstract:" and then try running it again.

```{r echo = T, results = 'hide', message=FALSE, warning=FALSE}
install.packages("tidyverse")
install.packages("readxl")
install.packages("ggplot2")
install.packages("tinytex")
install.packages("RColorBrewer")
install.packages("ggdist")
install.packages("waffle")
install.packages("dplyr")

library(tidyverse)
library(readxl)
library(ggplot2)
library(tinytex)
library(RColorBrewer)
library(ggdist)
library(waffle)
library(dplyr)
```

if that still doesnt work, please send me a message through github or however one gets an email sent to another person here.
