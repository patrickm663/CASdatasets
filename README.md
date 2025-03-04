<!-- README.md is generated from README.Rmd. Please edit that file -->
CASdatasets
======


Package description
-------------------

A collection of datasets, originally for the book 'Computational Actuarial Science with R' 
edited by Arthur Charpentier. Now, the package contains a large variety of actuarial datasets.


Install
-------

Please make sure that [xts](https://CRAN.R-project.org/package=xts), 
[sp](https://CRAN.R-project.org/package=sp), 
[zoo](https://CRAN.R-project.org/package=zoo) packages are installed

To get the current released version from [UQAM](http://cas.uqam.ca/),
[CNRS](http://dutangc.perso.math.cnrs.fr/RRepository/)
or my [website](http://dutangc.free.fr/pub/RRepos/):

``` r
install.packages("CASdatasets", repos = "http://dutangc.free.fr/pub/RRepos/", type="source")
#or 
install.packages("CASdatasets", repos = "http://dutangc.perso.math.cnrs.fr/RRepository/", type="source")
#or
install.packages("CASdatasets", repos = "http://cas.uqam.ca/pub/R/", type="source")
library(CASdatasets)
```

To get the current development version from github, you may try but much longer than downloading the source file from a repository.

``` r
install.packages("devtools")
devtools::install_github("dutangc/CASdatasets", subdir="pkg")
library(CASdatasets)
```


Todolist
-------


* add new datasets 
* remove the dependency on `sp` in order to move `sf` or `terra` packages, following https://r-spatial.org/r/2023/05/15/evolution4.html
* make a nice vignette to present each dataset visually
* make a NEWS file in markdown format
