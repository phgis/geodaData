
<!-- README.md is generated from README.Rmd. Please edit that file -->

# geodaData

<!-- badges: start -->

<!-- badges: end -->

The goal of geodaData is to store sample spatial datasets. These
datasets are intended to be used to teach basic spatial analysis
concepts. They are used in the weekly R Spatial Workshop at the Center
for Spatial Data Science at UChicago, and are based off of the [GeoDa
workbook](https://geodacenter.github.io/documentation.html) and [data
site](https://geodacenter.github.io/data-and-lab/) developed by Luc
Anselin and team.

## Installation

You can install the development version of geodaData from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("spatialanalysis/geodaData")
```

## Example

To use geodaData in a workshop, first load the package:

``` r
library(geodaData)
```

You will then be able to use the data in the package with a data() call,
similar to datasets included in base R.

``` r
data("nyc")
```

## Similar Packages

Interested in finding more R packages with spatial data included? Check
out:

  - [spData](https://github.com/Nowosad/spData): package with large
    variety of spatial datasets, accompanies the [Geocomputation with
    R](https://geocompr.github.io) book.
  - [tidycensus](https://github.com/walkerke/tidycensus) /
    [tigris](https://github.com/walkerke/tigris): API package for US
    Census data
