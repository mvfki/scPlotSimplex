# CytoSimplex <img src="man/figures/logo.png" align="right" width="120" />

[![R_CMD_check](https://github.com/welch-lab/CytoSimplex/actions/workflows/R_CMD_check.yml/badge.svg?branch=main)](https://github.com/welch-lab/CytoSimplex/actions/workflows/R_CMD_check.yml)[![codecov](https://codecov.io/gh/mvfki/CytoSimplex/branch/main/graph/badge.svg?token=AYU2AOE25I)](https://app.codecov.io/gh/mvfki/CytoSimplex)[![Seurat](https://img.shields.io/badge/Seurat-5.0.1-blue)](https://CRAN.R-project.org/package=Seurat)[![sce](https://img.shields.io/badge/SingleCellExperiment-1.22.0-blue)](https://bioconductor.org/packages/release/bioc/html/SingleCellExperiment.html)


CytoSimplex is an R package that creates simplex plot showing similarity between single-cells and terminals represented by clusters of cells. RNA velocity can be added as another layer of information.

For Python users, we have a Python package [CytoSimplex](https://github.com/welch-lab/pyCytoSimplex) that provides the same functionalities.

## Installation

The package is developed and tested under R>=4.2.0. Users can install R following the [instruction provided on CRAN](https://cran.r-project.org/). [RStudio](https://posit.co/downloads/) is a recommended IDE for working with R projects. 

To install CytoSimplex in R, run the following command in an R console:

```R
install.packages("CytoSimplex")
```

For the latest developmental version, run the following command in an R console:

```R
if (!requireNamespace("devtools", quietly = TRUE))
    install.packages("devtools")
devtools::install_github("welch-lab/CytoSimplex")
```

## Tutorial

We have created a [documentation website](https://welch-lab.github.io/CytoSimplex/) for posting [example tutorials](https://welch-lab.github.io/CytoSimplex/articles/CytoSimplex.html) walking through the process from loading the provided example data and creating different types of visualization.

