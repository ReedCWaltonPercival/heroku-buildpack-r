# Heroku Buildpack: R

<!-- [![Build Status][travis_img]][travis] -->

This is a [Heroku Buildpack][buildpacks] for applications which use [R][rproject] for statistical computing and [CRAN][cran] for R packages.

The buildpack supports the [heroku-16][stack16] and [heroku-18][stack18] stacks.

It also includes support for the [Packrat][packrat] and [renv][renv] package managers, and the [Shiny][shiny] and [Plumber][plumber] web application frameworks.

This version of the buildpack has been cloned from:  [`https://github.com/virtualstaticvoid/heroku-buildpack-r.git`][bpurl]. Provide it when creating your application on Heroku as follows:
