+++
date = "2016-04-21T02:50:28+02:00"
draft = false
title = "Welcome"
+++

# Welcome to the `tlverse`!

The `tlverse` is an effort to overhaul the Targeted Learning software ecosystem
in R. Inspired by the [`tidyverse`](https://tidyverse.org), we aim to construct
a collection of R packages that work well together and foster future development
in a unified fashion.

Currently, the tlverse is comprised of the following core packages:

* [`sl3`](https://tlverse.org/sl3/) for Super Learning
* [`tmle3`](https://tlverse.org/tmle3/) for Targeted Minimum Loss-based
    Estimation (TMLE)

as well as the following helper packages:

* [`delayed`](https://tlverse.org/delayed/) for parallelizing dependent tasks
* [`origami`](https://tlverse.org/origami/) for cross-validation

and packages for individual `tmle3` parameters:

* [`tmle3shift`](https://tlverse.org/tmle3shift/) Shift Intervention
* [`tmle3mopttx`](https://tlverse.org/tmle3mopttx/) Optimal Treatment

---

## Installation

Some of these packages are not yet available on
[CRAN](https://cran.r-project.org/), so for now the best option is to install
directly via GitHub using
[`devtools`](https://www.rstudio.com/products/rpackages/devtools/):

```
devtools::install_github("tlverse/tlverse")
```

---

## Getting Started

For now, the individual package pages are the best place to go to dive into the
`tlverse`. We hope to expand this site with documentation that spans across the
different packages, and provide a gentle introduction to the `tlverse` as a
whole.

