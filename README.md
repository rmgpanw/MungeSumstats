Standardise the format of summary statistics from GWAS with
*MungeSumstats*
================
Alan Murphy and Nathan Skene
2021-04-12

<!-- Readme.md is generated from Readme.Rmd. Please edit that file -->
<!-- badges: start -->

[![R-CMD-check](https://github.com/neurogenomics/MungeSumstats/workflows/R-CMD-check/badge.svg)](https://github.com/neurogenomics/MungeSumstats/actions)
<!-- badges: end -->

# Introduction

The *MungeSumstats* package is designed to facilitate the
standardisation of GWAS summary statistics as utilised in our Nature
Genetics paper.<sup>1</sup>

# Overview

The package is designed to handle the lack of standardisation of output
files by the GWAS community. There is a group who have now manually
standardised many GWAS: [R interface to the IEU GWAS database API •
ieugwasr](https://mrcieu.github.io/ieugwasr/) and
[gwasvcf](https://github.com/MRCIEU/gwasvcf) but because a lot of GWAS
remain closed access, these repositories are not all encompassing.

*MungeSumstats* provides a framework to standardise the format for any
GWAS summary statistics, including those in VCF format, enabling
downstream integration and analysis. The package works by addressing the
most common discrepancies across summary statistics.

# Installing MungeSumstats

The *MungeSumstats* package is available from github. To be able to
install the package one needs to run the following lines of code:

    if (!require("devtools")) {
      install.packages("devtools")
    }
    devtools::install_github("neurogenomics/MungeSumstats")

You can then load the package and data package:

``` r
library(MungeSumstats)
```

# Getting started

See the vignette for use cases of *MungeSumstats*.

If you have any problems please do file an issue here on github.

# Citation

If you use the MungeSumstats package as well then please cite

[Skene, et al. Genetic identification of brain cell types underlying
schizophrenia. Nature Genetics,
2018.](https://www.nature.com/articles/s41588-018-0129-5)

# References

<div id="refs" class="references csl-bib-body" line-spacing="2">

<div id="ref-Skene2018" class="csl-entry">

<span class="csl-left-margin">1. </span><span
class="csl-right-inline">Nathan G. Skene, T. E. B., Julien Bryois.
Genetic identification of brain cell types underlying schizophrenia.
*Nature Genetics* (2018).
doi:[10.1038/s41588-018-0129-5](https://doi.org/10.1038/s41588-018-0129-5)</span>

</div>

</div>
