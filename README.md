
<!-- README.md is generated from README.Rmd. Please edit that file -->

# censusviz

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/censusviz)](https://CRAN.R-project.org/package=censusviz)
<!-- badges: end -->

The goal of censusviz is to:

1.  converting historical demographic data from IPUMS into an accessible
    format for analysis and joining it with geospatial census tract data
    so that it is easy to visualize on a map,

2.  visualize the distribution of demographic data by census tract for a
    specified region and year on a leaflet map,

3.  create a simple shiny app that allows users to interactively explore
    changes over time in demographics through leaflet maps and data
    tables.

## Installation

`censusviz` is hosted on GitHub and can be installed by running the
following function:

``` r
remotes::install_github("rporta23/censusviz")
```

``` r
library(censusviz)
```

## Contributors

-   [Irene Foster](https://github.com/i-m-foster)
-   [Catherine Park](https://github.com/CJParkNW)
-   [Rose Porta](https://github.com/rporta23)