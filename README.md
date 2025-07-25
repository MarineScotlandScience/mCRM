
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mCRM <img src='docs/images/hexSticker.png' align="right" height="139" />

## A Shiny app to model collision risk of migratory birds in offshore wind farms

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

## Installation

You can install the github version of mCRM from here with:

``` r
devtools::install_github("HiDef-Aerial-Surveying/mCRM")
```

## mCRM usage (local)

Once installed as a package, the mCRM can be run like this:

``` r
library(mCRM)  ##Ensure this is run so all mCRM data are loaded to your environment
mCRM::run_app()
```

## mCRM usage (online)

You can access the mCRM on shinyapps.io:
<https://blackbawks.shinyapps.io/mCRM/>

## Using the interface

Instructions on running the tool can be found at
<https://marinescotlandscience.github.io/mCRM/>

## Reporting bugs

If you spot something out of place, please report it here:
<https://github.com/MarineScotlandScience/mCRM/issues>

## Information

The stochastic migration collision risk model (mCRM) shiny app was
developed by HiDef Aerial Surveying for Marine Scotland Science. This
tool is meant to be used to estimate the collision risk of migratory
birds passing through offshore windfarms.

The underlying functionality of the model is driven by the `stochLAB`
package, which can be found at
<https://github.com/MarineScotlandScience/stochLAB>. The stochLAB
package was developed by [DMP statistics](https://github.com/dmpstats)
and [HiDef Surveying](https://github.com/Hidef-Aerial-Surveying), and
maintained by [Black Bawks Data Science](https://github.com/blackbawks).

This tool is partnered with the stochastic collision risk model (sCRM)
tool, developed by [DMP statistics](https://github.com/dmpstats).
