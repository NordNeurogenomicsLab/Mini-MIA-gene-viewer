# Mini MIA gene viewer
App available at:  https://nordlab.shinyapps.io/MIA_RPKM_plots/

- Session info -----------------------------------------
 setting  value                       
 version  R version 4.0.2 (2020-06-22)
 os       Windows 10 x64              
 system   x86_64, mingw32             
 ui       RStudio                     
 language (EN)                        
 collate  English_United States.1252  
 ctype    English_United States.1252  
 tz       America/Los_Angeles         
 date     2021-02-23                  

- Packages ---------------------------------------------
 package      * version  date       lib source        
 askpass        1.1      2019-01-13 [1] CRAN (R 4.0.0)
 assertthat     0.2.1    2019-03-21 [1] CRAN (R 4.0.0)
 Cairo        * 1.5-12.2 2020-07-07 [1] CRAN (R 4.0.3)
 cli            2.2.0    2020-11-20 [1] CRAN (R 4.0.3)
 clipr          0.7.1    2020-10-08 [1] CRAN (R 4.0.3)
 colorspace     1.4-1    2019-03-18 [1] CRAN (R 4.0.0)
 crayon         1.3.4    2017-09-16 [1] CRAN (R 4.0.0)
 curl           4.3      2019-12-02 [1] CRAN (R 4.0.0)
 data.table   * 1.12.8   2019-12-09 [1] CRAN (R 4.0.0)
 digest         0.6.25   2020-02-23 [1] CRAN (R 4.0.0)
 dplyr        * 1.0.0    2020-05-29 [1] CRAN (R 4.0.0)
 DT           * 0.16     2020-10-13 [1] CRAN (R 4.0.3)
 ellipsis       0.3.1    2020-05-15 [1] CRAN (R 4.0.0)
 evaluate       0.14     2019-05-28 [1] CRAN (R 4.0.0)
 fansi          0.4.1    2020-01-08 [1] CRAN (R 4.0.0)
 farver         2.0.3    2020-01-16 [1] CRAN (R 4.0.0)
 fastmap        1.0.1    2019-10-08 [1] CRAN (R 4.0.0)
 generics       0.1.0    2020-10-31 [1] CRAN (R 4.0.3)
 ggplot2      * 3.3.2    2020-06-19 [1] CRAN (R 4.0.3)
 glue           1.4.1    2020-05-13 [1] CRAN (R 4.0.0)
 gtable         0.3.0    2019-03-25 [1] CRAN (R 4.0.0)
 htmltools      0.5.0    2020-06-16 [1] CRAN (R 4.0.2)
 htmlwidgets    1.5.3    2020-12-10 [1] CRAN (R 4.0.3)
 httpuv         1.5.4    2020-06-06 [1] CRAN (R 4.0.2)
 httr           1.4.2    2020-07-20 [1] CRAN (R 4.0.3)
 jsonlite       1.7.2    2020-12-09 [1] CRAN (R 4.0.3)
 kableExtra     1.3.1    2020-10-22 [1] CRAN (R 4.0.3)
 knitr          1.30     2020-09-22 [1] CRAN (R 4.0.3)
 labeling       0.4.2    2020-10-20 [1] CRAN (R 4.0.3)
 later          1.1.0.1  2020-06-05 [1] CRAN (R 4.0.2)
 lattice        0.20-41  2020-04-02 [2] CRAN (R 4.0.2)
 lifecycle      0.2.0    2020-03-06 [1] CRAN (R 4.0.0)
 magrittr       2.0.1    2020-11-17 [1] CRAN (R 4.0.3)
 Matrix         1.2-18   2019-11-27 [2] CRAN (R 4.0.2)
 mgcv           1.8-31   2019-11-09 [2] CRAN (R 4.0.2)
 mime           0.10     2021-02-13 [1] CRAN (R 4.0.4)
 munsell        0.5.0    2018-06-12 [1] CRAN (R 4.0.0)
 nlme           3.1-148  2020-05-24 [2] CRAN (R 4.0.2)
 openssl        1.4.3    2020-09-18 [1] CRAN (R 4.0.3)
 pacman         0.5.1    2019-03-11 [1] CRAN (R 4.0.3)
 pillar         1.4.7    2020-11-20 [1] CRAN (R 4.0.3)
 pkgconfig      2.0.3    2019-09-22 [1] CRAN (R 4.0.0)
 plyr           1.8.6    2020-03-03 [1] CRAN (R 4.0.0)
 profvis      * 0.3.7    2020-11-02 [1] CRAN (R 4.0.3)
 promises       1.1.1    2020-06-09 [1] CRAN (R 4.0.2)
 purrr          0.3.4    2020-04-17 [1] CRAN (R 4.0.0)
 R6             2.5.0    2020-10-28 [1] CRAN (R 4.0.3)
 RColorBrewer * 1.1-2    2014-12-07 [1] CRAN (R 4.0.0)
 Rcpp           1.0.6    2021-01-15 [1] CRAN (R 4.0.3)
 reshape2       1.4.4    2020-04-09 [1] CRAN (R 4.0.0)
 rlang          0.4.9    2020-11-26 [1] CRAN (R 4.0.3)
 rmarkdown    * 2.6      2020-12-14 [1] CRAN (R 4.0.2)
 rsconnect      0.8.16   2019-12-13 [1] CRAN (R 4.0.0)
 rstudioapi     0.13     2020-11-12 [1] CRAN (R 4.0.3)
 rvest          0.3.6    2020-07-25 [1] CRAN (R 4.0.3)
 scales         1.1.1    2020-05-11 [1] CRAN (R 4.0.0)
 sessioninfo  * 1.1.1    2018-11-05 [1] CRAN (R 4.0.3)
 shiny        * 1.5.0    2020-06-23 [1] CRAN (R 4.0.2)
 stringi        1.4.6    2020-02-17 [1] CRAN (R 4.0.0)
 stringr        1.4.0    2019-02-10 [1] CRAN (R 4.0.0)
 tibble         3.0.1    2020-04-20 [1] CRAN (R 4.0.0)
 tidyselect     1.1.0    2020-05-11 [1] CRAN (R 4.0.0)
 vctrs          0.3.0    2020-05-11 [1] CRAN (R 4.0.0)
 viridisLite    0.3.0    2018-02-01 [1] CRAN (R 4.0.0)
 webshot        0.5.2    2019-11-22 [1] CRAN (R 4.0.0)
 withr          2.3.0    2020-09-22 [1] CRAN (R 4.0.3)
 xfun           0.15     2020-06-21 [1] CRAN (R 4.0.2)
 xml2           1.3.2    2020-04-23 [1] CRAN (R 4.0.0)
 xtable         1.8-4    2019-04-21 [1] CRAN (R 4.0.0)
 yaml           2.2.1    2020-02-01 [1] CRAN (R 4.0.0)

[1] C:/Users/Karol/Documents/R/win-library/4.0
[2] C:/Program Files/R/R-4.0.2/library

