<!-- README.md is generated from README.Rmd. Please edit that file -->
miceds
======

Multivariate Imputation by Chained Equations for DataSHIELD
-----------------------------------------------------------

The [`mice`](https://github.com/stefvanbuuren/mice) package implements a popular method to deal with missing data. The package creates multiple imputations (replacement values) for multivariate missing data.

The [`DataSHIELD`](https://github.com/datashield) framework is a platform for federated data analysis that brings the algorithm to the data.

The [`miceds`](https://github.com/stefvanbuuren/miceds) package is an add-on to `mice` that makes multiple imputation available for federated data systems.

Installation
------------

The following code installs the `miceds` package:

``` r
install.packages("devtools")
devtools::install_github("stefvanbuuren/miceds")
```

Note
----

Warning: This is an experimental feature. These function do not yet actually work. If you have ideas about the integration of `mice` and `DataSHIELD` feel free to join in.

Related initiative
------------------

Related work appears in [`dsMice`](https://github.com/gflcampos/dsMice) and [`dsMiceClient`](https://github.com/gflcampos/dsMiceClient).

Minimal example
---------------

    Include minimal example here using public DataSHIELD nodes.
