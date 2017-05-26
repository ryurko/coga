# README #

[![Build Status](https://travis-ci.org/ChaoranHu/coga.svg?branch=master)](https://travis-ci.org/ChaoranHu/coga)

This README would normally document whatever steps are necessary to get your application up and running.

### What is this R package for? ###

* A calculation of convolution of gamma distributions in R. The convolution of gamma distributions is the sum of series of gamma distributions and all gamma distributions here can have different parameters. This package can calculate density function (`dcoga`), distribution function (`pcoga`), and do simulation work (`rcoga`).

* Version: 0.1.0.9000

### How do I get set up? ###

* Run the following R code.

```
install.packages("devtools")

## install package without vignette
devtools::install_github("ChaoranHu/coga")

## install package include vignette
devtools::install_github("ChaoranHu/coga", build_vignettes = TRUE)
```
or

```
install.packages("coga")
```

Note: Both ways need your computer have development tools. This package includes Cpp and C codes, so you need a CPP compiler (for mac, you can use Xcode, which can be installed from Apple Store). You may also need update your `R` in order to use `install.packages("coga")` way to install.

* Run `library(coga)` to load in R.

### How do I use Makefile? ###

* Download source form github

* Type `cd path_to_folder_include_package` in terminal.

* Use `make install` to install this package in terminal.

* Use `make build` to bundle this package in terminal.

* Use `make check` to do `R CMD check` for this package in terminal.

* Use `make clean` to clean generated files and remove installed package `coga` from local library in terminal.

### How do I use? ###

Please read vignette of this package by type `browseVignettes("coga")` in R, which includes several examples.

### Who do I talk to? ###

Chaoran Hu, <chaoran.hu@uconn.edu>

### Reference ###

[1] Moschopoulos, Peter G. "The distribution of the sum of independent gamma random variables." Annals of the Institute of Statistical Mathematics 37.1 (1985): 541-544.
