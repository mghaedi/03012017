MaryamGhaedi
================
MaryamGhaedi
1/10/2018

R Markdown
----------

``` r
library(tidyverse)
```

    ## ── Attaching packages ───────────────────────────────────────────────────────────────────────────────────────────── tidyverse 1.2.1 ──

    ## ✔ ggplot2 2.2.1     ✔ purrr   0.2.4
    ## ✔ tibble  1.4.1     ✔ dplyr   0.7.4
    ## ✔ tidyr   0.7.2     ✔ stringr 1.2.0
    ## ✔ readr   1.1.1     ✔ forcats 0.2.0

    ## ── Conflicts ──────────────────────────────────────────────────────────────────────────────────────────────── tidyverse_conflicts() ──
    ## ✖ dplyr::filter() masks stats::filter()
    ## ✖ dplyr::lag()    masks stats::lag()

``` r
ggplot(data = mpg) +  geom_point(mapping = aes(x = displ, y = hwy, size = class, color = drv))
```

    ## Warning: Using size for a discrete variable is not advised.

![](MaryamGhaedi_files/figure-markdown_github/unnamed-chunk-1-1.png)
