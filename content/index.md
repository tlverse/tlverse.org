+++
date = "2016-04-21T02:50:28+02:00"
draft = false
title = ""
+++
# Welcome to the tlverse!

The tlverse is an effort to overhaul the Targeted Learning software ecosystem in R. Inspired by the [tidyverse](https://tidyverse.org), we aim to construct a collection of R packages that work well together and foster further development in a unified fashion.

Currently, tlverse is comprised of the following core packages:

* [sl3](http://sl3.tlverse.org) for SuperLearning
* [tmle3](http://tmle3.tlverse.org/) for TMLE (Targeted Minimum Loss-based Estimation)

as well as the following helper packages: 

* [delayed](http://delayed.tlverse.org) for parallelizing dependent tasks
* [origami](http://origami.tlverse.org) for cross-validation

and packages for individual tmle3 parameters:

_coming soon_

## Installation

Some of these packages are not yet on CRAN, so for now the only option is to install directly via github using devtools:

```
devtools::install_github("jeremyrcoyle/tlverse")
```

## Getting Started

For now, the individual package pages are the best place to go to dive into the tlverse. We hope to expand this site with documentation that spans across the different packages, and provide a gentle introduction to the tlverse as a whole.
