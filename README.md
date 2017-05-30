
<!-- README.md is generated from README.Rmd. Please edit that file -->
<style>
small.tidyverse {display: none;}
</style>
The tidyverse
=============

Components
----------

<a href='http://dplyr.tidyverse.org'><img src='http://dplyr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://forcats.tidyverse.org'><img src='http://forcats.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://ggplot2.tidyverse.org'><img src='http://ggplot2.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://haven.tidyverse.org'><img src='http://haven.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://lubridate.tidyverse.org'><img src='http://lubridate.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://magrittr.tidyverse.org'><img src='http://magrittr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://purrr.tidyverse.org'><img src='http://purrr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://readr.tidyverse.org'><img src='http://readr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://readxl.tidyverse.org'><img src='http://readxl.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://stringr.tidyverse.org'><img src='http://stringr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://tibble.tidyverse.org'><img src='http://tibble.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://tidyr.tidyverse.org'><img src='http://tidyr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://tidyverse.tidyverse.org'><img src='http://tidyverse.tidyverse.org/logo.png' width='120' height='139' /></a>

The tidyverse is a collection of R packages that share common philosophies and are designed to work together. This site is a work-in-progress guide to the tidyverse and its packages.

If you are new to the tidyverse, the best place to learn the complete philsophy and how everything fits together is the [R for data science](http://r4ds.had.co.nz/) book. This book is available for free online, and can you order a physical copy from [Amazon](http://amzn.to/2aHLAQ1) (currently taking pre-orders, the book should be out by the end of the year).

Installation
------------

Install the complete tidyverse with a single line of code:

``` r
install.packages("tidyverse")
```

Load the **core** tidyverse packages: ggplot2, tibble, tidyr, [readr](http://readr.tidyverse.org), purrr, and dplyr. These are the packages you are likely to use in almost every analysis.

``` r
library(tidyverse)
#> + ggplot2 2.2.1             Date: 2017-05-23
#> + tibble  1.3.1                R: 3.4.0
#> + tidyr   0.6.2               OS: macOS Sierra 10.12.5
#> + readr   1.1.0              GUI: X11
#> + purrr   0.2.2.9000      Locale: en_US.UTF-8
#> + dplyr   0.6.0               TZ: America/Chicago
#> + stringr 1.2.0           
#> + forcats 0.2.0
#> ── Conflicts ────────────────────────────────────────────────────
#> * filter(),  from dplyr, masks stats::filter()
#> * lag(),     from dplyr, masks stats::lag()
```

Other resources
---------------

-   [Tidyverse style guide](http://style.tidyverse.org)
