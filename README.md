
<!-- README.md is generated from README.Rmd. Please edit that file -->

# geokodigo: An Interface to the Philippine Standard Geographic Codes

<!-- badges: start -->

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/panukatan/geokodigo/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/panukatan/geokodigo/actions/workflows/R-CMD-check.yaml)
[![test-coverage](https://github.com/panukatan/geokodigo/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/panukatan/geokodigo/actions/workflows/test-coverage.yaml)
[![Codecov test
coverage](https://codecov.io/gh/panukatan/geokodigo/branch/main/graph/badge.svg)](https://app.codecov.io/gh/panukatan/geokodigo?branch=main)
[![CodeFactor](https://www.codefactor.io/repository/github/panukatan/geokodigo/badge)](https://www.codefactor.io/repository/github/panukatan/geokodigo)
<!-- badges: end -->

The Philippine Standard Geographic Code (PSGC) is a classification and
coding of the geographical-political subdivisions of the country, such
as the region, the province, the municipality/city and the barangay. The
PSGC is currently compiled and updated quarterly through a collaborative
effort of the Philippine Statistics Authority (PSA) and its interagency
Technical Working Group on Geographic Code (TWGGC) composed of the
Department of the Interior and Local Government (DILG), Commission on
Elections (COMELEC), National Mapping and Resource Information Authority
(NAMRIA), and the Land Management Bureau (LMB). This package provides
utilities for accessing different versions of the PSGC over time,
formatting and structuring them into machine-readable formats.

## What does `geokodigo` do?

Please note that `geokodigo` is still highly experimental and is
undergoing a lot of development. Hence, any functionalities described
below and in the rest of the package documentation have a high
likelihood of changing interface or approach as we aim for a stable
working version.

Currently, the package provides the following functionalities:

- Retrieval and/or download of quarterly PSGC updates released by the
  PSA on their website;

- Standardised naming of PSGC release files;

- Upload and/or archive raw quarterly PSGC releases onto specific
  platforms; and,

- Process quarterly PSGC releases into machine-readable and relational
  database-ready structures.

## Installation

`geokodigo` is not yet on CRAN but can be installed from the [panukatan
R universe](https://panukatan.r-universe.dev) as follows:

``` r
install.packages(
  "geokodigo",
  repos = c('https://panukatan.r-universe.dev', 'https://cloud.r-project.org')
)
```

## Usage

## Citation

If you find the `geokodigo` package useful please cite using the
suggested citation provided by a call to the `citation()` function as
follows:

``` r
citation("geokodigo")
#> To cite geokodigo in publications use:
#> 
#>   Ernest Guevarra (2024). geokodigo: An Interface to the Philippine
#>   Standard Geographic Codes R package version 0.0.0.9000 URL
#>   https://panukatan.io/geokodigo/
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {geokodigo: An Interface to the Philippine Standard Geographic Codes},
#>     author = {{Ernest Guevarra}},
#>     year = {2024},
#>     note = {R package version 0.0.0.9000},
#>     url = {https://panukatan.io/geokodigo/},
#>   }
```

## Community guidelines

Feedback, bug reports and feature requests are welcome; file issues or
seek support [here](https://github.com/panukatan/geokodigo/issues). If
you would like to contribute to the package, please see our
[contributing
guidelines](https://panukatan.io/geokodigo/CONTRIBUTING.html).

This project is released with a [Contributor Code of
Conduct](https://panukatan.io/geokodigo/CODE_OF_CONDUCT.html). By
participating in this project you agree to abide by its terms.
