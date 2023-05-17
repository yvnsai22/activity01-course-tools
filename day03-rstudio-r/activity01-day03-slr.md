Simple Linear Regression Analysis
================

`{global-options, include=FALSE} knitr::opts_chunk$set(echo = TRUE)`

## Introduction

This will likely be the only `.Rmd` file that I provide to you as all
other activities will have you follow directions in the day-specific
folder’s `README` and type your own “report” in an Rmarkdown document
that you create. Note that when I type in Rmarkdown files, each sentence
begins on its own line. This helps me to quickly find errors and correct
them, but you do not need to use this method.

If I want to start a new paragraph, I simply press Enter/Return twice to
create a new “block”. Below is an R code chunk named
“simple-calculations”. When I am working in Rmarkdown documents, I make
sure that every code chunk has a descriptive title. This is a suggestion
that I strongly recommend that you follow. We will see how naming code
chunks makes our life easier later in this document so be sure to stick
around.

## Adding values 2 and 5

``` r
Adding <- 2 + 5
```

## Creating R object called ‘int\_vect’

``` r
int_vect <- 1:9
```

## Creating R object called ‘char\_vect’

``` r
char_vect <- letters[1:17]
```

## Determining number of items occuring after letter “D”

``` r
items_after_D <- sum(char_vect > "D")
```
