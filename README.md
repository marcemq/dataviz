Data Visualization
================

<!-- README.md is generated from README.Rmd -->
Setup
-----

-   Download and install [R](https://cran.r-project.org/) and [RStudio](https://rstudio.com/products/rstudio/).
-   Execute `available.packages()` in RStudio console, if it hangs a proxy setup is required, and to do so follow the next steps:

``` r
file.edit('~/.Renviron')
# Fill the Renviron document with your proxy entries, i.e.:
http_proxy=http://my-proxy.com:911
https_proxy=http://my-proxy.com:912
# Restart Rstudio for the env variable to be considered
```

-   The source of this documents is purely [R Markdown](https://rmarkdown.rstudio.com/index.html) and to regenerate the `.md` files so can be properly rendered in github follow the next steps:

``` r
# change the output entry in yaml header
output: rmarkdown::github_document
# for storing the generated images in a separate folder at document setup
knitr::opts_chunk$set(fig.path = "README_figs/README-")
```
