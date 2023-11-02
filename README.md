# Everyday-R
This repository contains a collection of Markdown files compiled with `bookdown` for the open-source book `Everyday-R` hosted [here](https://bookdown.org/brianjmpark/everydayR/). Each chapter aims to help learners of R programming language learn the practical syntax and usage of R in context of data science tasks such as data wrangling, data exploration, and machine learning.  

**This book is a work in progress and is not complete!**

## Table of contents
#### 1. [Introduction](https://bookdown.org/brianjmpark/everydayR/#introduction)
#### 2. [Everyday data wrangling](https://bookdown.org/brianjmpark/everydayR/everyday-data-wrangling.html)
#### 3. [Everyday Iterations](https://bookdown.org/brianjmpark/everydayR/everyday-iterations.html)
#### 4. [Interlude I: A brief glimpse into `data.table`](https://bookdown.org/brianjmpark/everydayR/interlude-i-a-brief-glimpse-into-data.html)
#### 5. [Everyday exploratory data analysis](https://bookdown.org/brianjmpark/everydayR/everyday-exploratory-data-analysis.html)
#### 6. [Everyday ML: Classification](https://bookdown.org/brianjmpark/everydayR/everyday-ml-classification.html)
#### 7. [Everyday ML: Regression](https://bookdown.org/brianjmpark/everydayR/everyday-ml-regression.html)
## Resources
* [R for data science by Hadley Wickham](https://r4ds.had.co.nz/)
* [Advanced R by Hadley Wickham](https://adv-r.hadley.nz/)
* [Tidyverse documentation](https://www.tidyverse.org/)
* [Caret documentation](https://topepo.github.io/caret/)
* [Shiny cheatsheet](https://shiny.rstudio.com/images/shiny-cheatsheet.pdf)

## My other projects
* [Visualizing stats from the Premier League using Shiny and web scraping](https://github.com/snowoflondon/PL_Visualizer)
* [Calculation of drug synergy using linear models and Shiny](https://github.com/snowoflondon/CIComputeR_WEB)
* [Dose-response model estimate analysis using drc on Shiny](https://github.com/snowoflondon/LL4R)

## Companion blog
* [Data science blog covering fundamental concepts with R & Python code](https://brianjmpark.github.io/)

## Footnote
All source code used to compile the book, including all code chunks and original markdown files are stored in this repository. The book is hosted on the `shinyapps.io` server and compiled using the R package `bookdown`. For more information on `bookdown`, check their [documentations](https://bookdown.org/yihui/bookdown/get-started.html)

## R sessionInfo()
```{r}
R version 4.3.1 (2023-06-16)
Platform: aarch64-apple-darwin20 (64-bit)
Running under: macOS Big Sur 11.2.3

Matrix products: default
BLAS:   /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib 
LAPACK: /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/lib/libRlapack.dylib;  LAPACK version 3.11.0

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

time zone: America/Toronto
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] gridExtra_2.3    factoextra_1.0.7 bookdown_0.34    rsconnect_1.0.1 
 [5] broom_1.0.5      lubridate_1.9.2  forcats_1.0.0    stringr_1.5.0   
 [9] dplyr_1.1.2      purrr_1.0.1      readr_2.1.4      tidyr_1.3.0     
[13] tibble_3.2.1     ggplot2_3.4.2    tidyverse_2.0.0 

loaded via a namespace (and not attached):
 [1] gtable_0.3.3     compiler_4.3.1   Rcpp_1.0.10      tidyselect_1.2.0
 [5] scales_1.2.1     yaml_2.3.7       fastmap_1.1.1    R6_2.5.1        
 [9] generics_0.1.3   knitr_1.43       backports_1.4.1  ggrepel_0.9.3   
[13] munsell_0.5.0    pillar_1.9.0     tzdb_0.4.0       rlang_1.1.1     
[17] utf8_1.2.3       stringi_1.7.12   xfun_0.39        timechange_0.2.0
[21] cli_3.6.1        withr_2.5.0      magrittr_2.0.3   digest_0.6.31   
[25] grid_4.3.1       rstudioapi_0.14  hms_1.1.3        lifecycle_1.0.3 
[29] vctrs_0.6.3      evaluate_0.21    glue_1.6.2       fansi_1.0.4     
[33] colorspace_2.1-0 rmarkdown_2.22   tools_4.3.1      pkgconfig_2.0.3 
[37] htmltools_0.5.5
```
