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
build_site()
serve_site()
```

Changes are mostly made in `SAMOWebv1/content/`. As soon as it is pushed to GitHub it will be displayed on the website given it passes the `build_site()`.
