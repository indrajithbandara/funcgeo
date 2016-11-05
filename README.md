
<!-- README.md is generated from README.Rmd. Please edit that file -->
funcgeo
=======

The goal of funcgeo is to reproduce the pictures in the following papers:

-   <http://users.ecs.soton.ac.uk/peter/funcgeo.pdf>
-   <http://eprints.soton.ac.uk/257577/1/funcgeo2.pdf>

Installation
------------

You can install funcgeo from my Drat repository on Github:

``` r
# install.packages("drat")
drat::addRepo("MHenderson")
install.packages("funcgeo")
```

Examples
--------

``` r
library(funcgeo)
library(grid)

grid.draw(cycle(rot(fish_q)))
```

![](README_files/figure-markdown_github/unnamed-chunk-1-1.png)

Please note that this project is released with a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.
