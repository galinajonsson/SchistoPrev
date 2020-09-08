# Schistosomoes Prevalence

Author(s): [Galina M. Jönsson](https://github.com/galinajonsson) insert MORE

This repository contains all the code and some data for:



## Data
INFO ON DATA AND DATA AVAILABILITY

For reproducibility purposes, download this and place it into the `Data/rawdata/` folder to rerun our analyses. 


## Analyses
The analyses code is divided into .Rmd files that run the analyses for each section of the manuscript/supplementary materials, more detailed scripts for some functions used in analyses and called by the .Rmd files, and scripts for the figures found in the manuscript.


* __01-data-cleaning-Rdm__ cleans and standardises the georeferenced data.
* __02-format-model.Rdm__ formats the clean data and runs the models.
* __03-summaries.Rmd__ summarises the data used in models and model outputs.

##### Code for figures

* __figure-record_numbers.R__



##### Code for functions

* __function-readRDS_multi.R__


## Other folders

* `/figs` contains the figures with file names matching those of the manuscript


## Session Info
For reproducibility purposes, here is the output of devtools::session_info() used to perform the analyses in the publication.
```
─ Session info ───────────────────────────────────────────────────────────────────────────────────────────────────────
 setting  value                       
 version  R version 4.0.2 (2020-06-22)
 os       macOS Catalina 10.15.6      
 system   x86_64, darwin17.0          
 ui       RStudio                     
 language (EN)                        
 collate  en_GB.UTF-8                 
 ctype    en_GB.UTF-8                 
 tz       Europe/London               
 date     2020-09-08                  

─ Packages ───────────────────────────────────────────────────────────────────────────────────────────────────────────
 package      * version  date       lib source        
 abind          1.4-5    2016-07-21 [1] CRAN (R 4.0.2)
 arm          * 1.11-2   2020-07-27 [1] CRAN (R 4.0.2)
 assertthat     0.2.1    2019-03-21 [1] CRAN (R 4.0.2)
 backports      1.1.9    2020-08-24 [1] CRAN (R 4.0.2)
 base64enc      0.1-3    2015-07-28 [1] CRAN (R 4.0.2)
 boot           1.3-25   2020-04-26 [1] CRAN (R 4.0.2)
 callr          3.4.4    2020-09-07 [1] CRAN (R 4.0.2)
 carData      * 3.0-4    2020-05-22 [1] CRAN (R 4.0.2)
 checkmate      2.0.0    2020-02-06 [1] CRAN (R 4.0.2)
 cli            2.0.2    2020-02-28 [1] CRAN (R 4.0.2)
 cluster        2.1.0    2019-06-19 [1] CRAN (R 4.0.2)
 coda           0.19-3   2019-07-05 [1] CRAN (R 4.0.2)
 colorspace     1.4-1    2019-03-18 [1] CRAN (R 4.0.2)
 crayon         1.3.4    2017-09-16 [1] CRAN (R 4.0.2)
 data.table     1.13.0   2020-07-24 [1] CRAN (R 4.0.2)
 DBI            1.1.0    2019-12-15 [1] CRAN (R 4.0.2)
 desc           1.2.0    2018-05-01 [1] CRAN (R 4.0.2)
 devtools       2.3.1    2020-07-21 [1] CRAN (R 4.0.2)
 digest         0.6.25   2020-02-23 [1] CRAN (R 4.0.2)
 dplyr        * 1.0.2    2020-08-18 [1] CRAN (R 4.0.2)
 effects      * 4.2-0    2020-08-11 [1] CRAN (R 4.0.2)
 ellipsis       0.3.1    2020-05-15 [1] CRAN (R 4.0.2)
 evaluate       0.14     2019-05-28 [1] CRAN (R 4.0.1)
 fansi          0.4.1    2020-01-08 [1] CRAN (R 4.0.2)
 FNN            1.1.3    2019-02-15 [1] CRAN (R 4.0.2)
 foreign        0.8-80   2020-05-24 [1] CRAN (R 4.0.2)
 Formula      * 1.2-3    2018-05-03 [1] CRAN (R 4.0.2)
 fs             1.5.0    2020-07-31 [1] CRAN (R 4.0.2)
 generics       0.0.2    2018-11-29 [1] CRAN (R 4.0.2)
 ggplot2      * 3.3.2    2020-06-19 [1] CRAN (R 4.0.2)
 glue           1.4.2    2020-08-27 [1] CRAN (R 4.0.2)
 gridExtra      2.3      2017-09-09 [1] CRAN (R 4.0.2)
 gstat        * 2.0-6    2020-05-18 [1] CRAN (R 4.0.2)
 gtable         0.3.0    2019-03-25 [1] CRAN (R 4.0.2)
 Hmisc        * 4.4-1    2020-08-10 [1] CRAN (R 4.0.2)
 htmlTable      2.0.1    2020-07-05 [1] CRAN (R 4.0.2)
 htmltools      0.4.0    2019-10-04 [1] CRAN (R 4.0.2)
 htmlwidgets    1.5.1    2019-10-08 [1] CRAN (R 4.0.2)
 insight        0.9.5    2020-09-07 [1] CRAN (R 4.0.2)
 intervals      0.15.2   2020-04-04 [1] CRAN (R 4.0.2)
 jpeg           0.1-8.1  2019-10-24 [1] CRAN (R 4.0.2)
 knitr          1.29     2020-06-23 [1] CRAN (R 4.0.2)
 lattice      * 0.20-41  2020-04-02 [1] CRAN (R 4.0.2)
 latticeExtra   0.6-29   2019-12-19 [1] CRAN (R 4.0.2)
 lifecycle      0.2.0    2020-03-06 [1] CRAN (R 4.0.2)
 lme4         * 1.1-23   2020-04-07 [1] CRAN (R 4.0.1)
 magrittr       1.5      2014-11-22 [1] CRAN (R 4.0.2)
 MASS         * 7.3-51.6 2020-04-26 [1] CRAN (R 4.0.2)
 Matrix       * 1.2-18   2019-11-27 [1] CRAN (R 4.0.2)
 memoise        1.1.0    2017-04-21 [1] CRAN (R 4.0.2)
 minqa          1.2.4    2014-10-09 [1] CRAN (R 4.0.2)
 mitools        2.4      2019-04-26 [1] CRAN (R 4.0.2)
 munsell        0.5.0    2018-06-12 [1] CRAN (R 4.0.2)
 nlme           3.1-148  2020-05-24 [1] CRAN (R 4.0.2)
 nloptr         1.2.2.2  2020-07-02 [1] CRAN (R 4.0.2)
 nnet           7.3-14   2020-04-26 [1] CRAN (R 4.0.2)
 pillar         1.4.6    2020-07-10 [1] CRAN (R 4.0.2)
 pkgbuild       1.1.0    2020-07-13 [1] CRAN (R 4.0.2)
 pkgconfig      2.0.3    2019-09-22 [1] CRAN (R 4.0.2)
 pkgload        1.1.0    2020-05-29 [1] CRAN (R 4.0.2)
 png            0.1-7    2013-12-03 [1] CRAN (R 4.0.2)
 prettyunits    1.1.1    2020-01-24 [1] CRAN (R 4.0.2)
 processx       3.4.4    2020-09-03 [1] CRAN (R 4.0.2)
 ps             1.3.4    2020-08-11 [1] CRAN (R 4.0.2)
 purrr          0.3.4    2020-04-17 [1] CRAN (R 4.0.2)
 R6             2.4.1    2019-11-12 [1] CRAN (R 4.0.2)
 RColorBrewer   1.1-2    2014-12-07 [1] CRAN (R 4.0.2)
 Rcpp           1.0.5    2020-07-06 [1] CRAN (R 4.0.2)
 remotes        2.2.0    2020-07-21 [1] CRAN (R 4.0.2)
 rlang          0.4.7    2020-07-09 [1] CRAN (R 4.0.2)
 rmarkdown      2.3      2020-06-18 [1] CRAN (R 4.0.2)
 rpart          4.1-15   2019-04-12 [1] CRAN (R 4.0.2)
 rprojroot      1.3-2    2018-01-03 [1] CRAN (R 4.0.2)
 rstudioapi     0.11     2020-02-07 [1] CRAN (R 4.0.2)
 scales         1.1.1    2020-05-11 [1] CRAN (R 4.0.2)
 sessioninfo    1.1.1    2018-11-05 [1] CRAN (R 4.0.2)
 sp           * 1.4-2    2020-05-20 [1] CRAN (R 4.0.2)
 spacetime      1.2-3    2020-01-21 [1] CRAN (R 4.0.2)
 statmod        1.4.34   2020-02-17 [1] CRAN (R 4.0.2)
 stringi        1.4.6    2020-02-17 [1] CRAN (R 4.0.2)
 stringr        1.4.0    2019-02-10 [1] CRAN (R 4.0.2)
 survey         4.0      2020-04-03 [1] CRAN (R 4.0.2)
 survival     * 3.1-12   2020-04-10 [1] CRAN (R 4.0.2)
 testthat       2.3.2    2020-03-02 [1] CRAN (R 4.0.2)
 tibble         3.0.3    2020-07-10 [1] CRAN (R 4.0.2)
 tidyselect     1.1.0    2020-05-11 [1] CRAN (R 4.0.2)
 usethis        1.6.1    2020-04-29 [1] CRAN (R 4.0.2)
 vctrs          0.3.4    2020-08-29 [1] CRAN (R 4.0.2)
 withr          2.2.0    2020-04-20 [1] CRAN (R 4.0.2)
 xfun           0.16     2020-07-24 [1] CRAN (R 4.0.2)
 xts            0.12-0   2020-01-19 [1] CRAN (R 4.0.2)
 yaml           2.2.0    2018-07-25 [1] CRAN (R 4.0.2)
 zoo            1.8-8    2020-05-02 [1] CRAN (R 4.0.2)
 ```