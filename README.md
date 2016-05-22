
<!-- README.md is generated from README.Rmd. Please edit that file -->
eechidna
========

[![Travis-CI Build Status](https://travis-ci.org/ropenscilabs/eechidna.svg?branch=master)](https://travis-ci.org/ropenscilabs/eechidna) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/ropenscilabs/eechidna?branch=master&svg=true)](https://ci.appveyor.com/project/ropenscilabs/eechidna)

Exploring Election and Census Highly Informative Data Nationally for Australia
------------------------------------------------------------------------------

The R package *eechidna* provides data from the 2013 Australian Federal Election and 2011 Australian Census for each House of Representatives electorate, along with some tools for visualizing and analysing the data.

This package was developed during the [rOpenSci auunconf event](http://auunconf.ropensci.org/) in Brisbane, Queensland, during 21-22 April 2016. [Peter Ellis'](https://github.com/ellisp/) work on the NZ electoral data was an important inspiration for this package.

How to install
--------------

You can install the package from github using `devtools`, like this:

``` r
devtools::install_github("ropenscilabs/eechidna")
library(eechidna)
```

How to use
----------

The most accessible and impressive part of this package is a highly interactive web app for exploring the election and census data together. This app uses the shiny framework, and can be run locally on your computer with the command `eechidna::launchApp()`. There is a video demo of the app here: <https://vimeo.com/167367369>

In addition to the app, the package consists of several datasets, including the 2011 Australian Census, the 2013 Australian Federal Election (House of Representatives), and shapefiles for all Australian electoral districts.

We have two vignettes that show how to access these data in the package, and demonstrate how to analyse the data using R:

-   'Exploring the 2013 Election data'
-   'Exploring the 2011 Census data'

There are also two vignettes that demonstrate how to use the spatial data to make maps. Mapping election data for Australia is not trivial because of the extreme variation in electorate size. In these vignettes we show some methods for effectively visualising election data in Australia:

-   'Mapping Australia's Electorates'
-   'Plotting Australia's Polling Stations'

License
-------

This package is free and open source software, licensed under GPL (&gt;= 2).

Feedback, contributing, etc.
----------------------------

Please open and issue if you find something that doesn't work as expected or have questions or suggestions. Note that this project is released with a [Guide to Contributing](CONTRIBUTING.md) and a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.

Acknoweldgements
----------------

Thanks to Xiaoyue Cheng for her [cartogram](https://github.com/chxy/cartogram) package which supplies the Dorling algorithm for this package. Thanks also to Andy Teucher for his [rmapshaper](https://github.com/ateucher/rmapshaper) package which has some key functions for working with shapefiles. Thanks to Scott Chamberlain and Yihui Xie for help with troubleshooting.

------------------------------------------------------------------------

[![ropensci\_footer](http://ropensci.org/public_images/github_footer.png)](http://ropensci.org)
