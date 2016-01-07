[![Build Status](https://travis-ci.org/stan-dev/rstanarm.svg?branch=master)](https://travis-ci.org/stan-dev/rstanarm) [![Coverage Status](https://img.shields.io/codecov/c/github/stan-dev/rstanarm/master.svg)](https://codecov.io/github/stan-dev/rstanarm?branch=master) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/rstanarm)](http://cran.r-project.org/package=rstanarm)


rstanarm
========
This is an R package that emulates other R model-fitting functions but uses (R)Stan for the back-end estimation. 
The primary target audience is people who would be open to Bayesian inference if using Bayesian software were easy 
but would use frequentist software otherwise. That said, this R package often uses posterior medians as point estimates.

### Installation

rstanarm is not yet on CRAN. To install it, first make sure that you can install rstan by following these [instructions](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started) . Then, execute in R
```{r}
if (!require(devtools)) {
  install.packages("devtools")
  library(devtools)
}
devtools::install_github("stan-dev/rstanarm", args = "--preclean")
```

### Contributing 

If you are interested in contributing to the development of **rstanarm** please see the [Contributing to development](https://github.com/stan-dev/rstanarm/wiki/Contributing-to-development) page of the wiki.
