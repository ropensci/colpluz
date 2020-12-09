rcol
====



<!-- README.md is generated from README.Rmd. Please edit that file -->

[![R-CMD-check](https://github.com/ropensci/rcol/workflows/R-CMD-check/badge.svg)](https://github.com/ropensci/rcol/actions)
[![codecov](https://codecov.io/gh/ropensci/rcol/branch/master/graph/badge.svg)](https://codecov.io/gh/ropensci/rcol)

`rcol` is a R client for the Catalogue of Life Plus

Package documentation: https://docs.ropensci.org/rcol/

* Catalogue of Life: http://www.catalogueoflife.org/
* Catalogue of Life Plus: https://github.com/CatalogueOfLife/general
* COL+ API docs: https://api.catalogue.life/
* Web portal for COL+: https://data.catalogue.life/

## Installation


```r
remotes::install_github("ropensci/rcol")
# OR
install.packages("rcol", repos="https://dev.ropensci.org")
```


```r
library("rcol")
```

<!-- API notes
* `/dataset/{dataset_key}/taxon/` routes contain the data given in `/dataset/{dataset_key}/name/` routes -->

## Meta

* Please [report any issues or bugs](https://github.com/ropensci/rcol/issues).
* License: MIT
* Get citation information for `rcol` in R doing `citation(package = 'rcol')`
* Please note that this package is released with a [Contributor Code of Conduct](https://ropensci.org/code-of-conduct/). By contributing to this project, you agree to abide by its terms.
