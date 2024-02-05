
# r2diitemplate

[![Project Status: Unsupported – The project has reached a stable, usable state but the author(s) have ceased all work on it. A new maintainer may be desired.](https://www.repostatus.org/badges/latest/unsupported.svg)](https://www.repostatus.org/#unsupported)

**This project is archived for future reference, but no new work is expected in this repository. Future work is expected to be based off [pacta.r.package`](https://github.com/RMI-PACTA/pacta.r.package).**

<!-- badges: start -->
<!-- badges: end -->

r2diitemplate provides a custom pkgdown template for 2dii packages. Please don't use it for your own package if it's not a 2dii package.

inspired by [tidytemplate](https://github.com/tidyverse/tidytemplate/) and [rotemplate](https://github.com/ropensci-org/rotemplate)

meant to follow the limited documentation of a [pkgdown template](https://pkgdown.r-lib.org/articles/customise.html#template-packages)


## Installation

You can install the development version of r2diitemplate from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("2DegreesInvesting/r2diitemplate")
```


## Usage

Set it as your site's theme in `_pkgdown.yaml`:

```yml
template:
  package: r2diitemplate
```

If you're building your site using a GitHub action or other similar tool, you'll also need to install r2diitemplate in the runner. If you're using the [r-lib pkgdown workflow](https://github.com/r-lib/actions/blob/v2-branch/examples/pkgdown.yaml), you can add the following line to your DESCRIPTION:

```
Config/Needs/website: 2DegreesInvesting/r2diitemplate
```
