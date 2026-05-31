
<!-- README.md is generated from README.Rmd. Please edit that file -->

# acuitydown <a href="https://ascentsoftware.github.io/acuitydown/"><img src="man/figures/logo.svg" align="right" height="139" alt="acuitydown website" /></a>

<!-- badges: start -->

<!-- badges: end -->

A pkgdown template for Acuity Analytics R packages.

## Installation

``` r
# install.packages("pak")
pak::pak("ascentsoftware/acuitydown")
```

## Usage

Add to `DESCRIPTION` of to-be-documented package:

    Config/Needs/website: ascentsoftware/acuitydown

And in `_pkgdown.yml`:

``` yml
template:
  package: acuitydown
  bootstrap: 5
```
