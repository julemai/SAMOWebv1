# SAMO website

This is the repo for the SAMO group website which is now live at www.sensitivityanalysis.org


## Getting things run in developer mode in Rstudio

First some packages need to be installed
```
# install packages
install.packages("blogdown")
library(blogdown)
blogdown::install_hugo()
```

To get a local compile of the website
```
# get local website built
setwd("~/Documents/GitHub/SAMOWebv1")
library(blogdown)
serve_site()
```
