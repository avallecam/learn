---
title: Reproducibility using R
author: Thibaut Jombart
authors: ["Thibaut Jombart"]
categories: ["lectures"]
topics: ["rmarkdown", "data science", "reproducibility"]
date: 2019-11-19
image: img/highres/printing-press.jpg
slug: reproducibility
showonlyimage: true
css: css/custom.css
licenses: CC-BY
---

Beyond the availability of data and methods, reproducible science requires the traceability of analyses. Whether it is for yourself or for collaborators, as series of tools and good practices can facilitate your work flow, simplify analyses, and prevent the loss of data and results. This lecture provides an introduction to reproducibility using **R**.

Slides
======

**Click on the image below to access the slides:**

<center>
<a href="../../slides/reproducibility/reproducibility.html"><img class="gateway" src="../../img/highres/printing-press.jpg" width="50%" alt="click there for slides" align="middle"></a>
</center>
Related packages
================

`knitr`
-------

`knitr` provides excellent resources for literate programming mixing **R** with [*LaTeX*](https://en.wikipedia.org/wiki/LaTeX) or [*markdown*](https://en.wikipedia.org/wiki/Markdown).

It is extensively documented at: <https://yihui.name/knitr/>

To install the current stable, CRAN version of the package, type:

``` r
install.packages("knitr")
```

To benefit from the latest features and bug fixes, install the development version of the package using:

``` r
update.packages(ask = FALSE, repos = 'https://cran.rstudio.org')
install.packages('knitr', repos = c('https://xran.yihui.name', 'https://cran.rstudio.org'))
```

`rmarkdown`
-----------

`rmarkdown` extends the capabilities of `knitr` with a more diverse set of outputs generated from `Rmd` files, including pdf documents, article templates, pdf or html slides, or even web applications.

More information on `rmarkdown` is available from: <http://rmarkdown.rstudio.com/>.

To install this package, type:

``` r
install.packages("rmarkdown")
```

For the devel version, type (uses `devtools`):

``` r
devtools::install_github("rstudio/rmarkdown")
```

`lintr`
-------

`lintr` will analyse your code and point out deviations from current good coding practices. It can be ran on a `.R` file, but also can be used to analyse code typed in real-time for a number of coding platforms including Rstudio, emacs and others.

For more information on this package, go to: <https://github.com/jimhester/lintr>.

To install this package, type:

``` r
install.packages("lintr")
```

`reportfactory`
---------------

The `reportfactory` provides an infrastructure for handling multiple `Rmd` reports which need regular updating.

For more information on this package, go to: <https://github.com/reconhub/reportfactory>.

To install this package, type:

``` r
remotes::install_github("reconhub/reportfactory")
```

Other resources
===============

Golden rules for writing analysis reports
-----------------------------------------

These golden rules list several coding and statistical practices aimed at improving readability and robustness of analysis reports. Click on [this link](https://github.com/reconhub/guides/raw/master/golden_rules.html.zip) to download the current version, or visit [this page](https://github.com/reconhub/guides) for more information.

Report factory templates
------------------------

This repository provides templates of report factories based on existing factories. Visit the [github project](https://github.com/reconhub/report_factories_templates) for more information.

R4epi templates
---------------

The *R4epi* project provides several templates for epidemiological data analysis. Visit their [website](https://r4epis.netlify.com/) for more information.

About this document
===================

Contributors
------------

-   Thibaut Jombart: initial version

Contributions are welcome via [pull requests](https://github.com/reconhub/learn/pulls). The source files include:

-   [**the slides**](https://raw.githubusercontent.com/reconhub/learn/master/static/slides/reproducibility/reproducibility.Rmd)

-   [**this document**](https://raw.githubusercontent.com/reconhub/learn/master/content/post/reproducibility.Rmd)

Legal stuff
-----------

**License**: [CC-BY](https://creativecommons.org/licenses/by/3.0/) **Copyright**: Thibaut Jombart, 2017
