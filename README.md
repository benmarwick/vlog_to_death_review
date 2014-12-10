## Supplementary materials for an Open Review for _Internet Archaeology_

### Compendium DOI: 
 
### Author of this repository:

Ben Marwick (benmarwick@gmail.com)

### Published in: 


## Use

The simplest way to access the code and data is to download and unzip the repository from here:

https://github.com/benmarwick/vlog_to_death_review/archive/master.zip  

Then open and run the rmd file in RStudio.

### Contents:

This repository contains code and data used to accompany my open review of Tong et al. "Vlog to Death: Project Eliseg’s Video-Blogging", submitted to _Internet Archaeology_. 

The `vlog_review.rmd` file includes the R code and narrative text of my review.

In the /vlog_review_data directory: 

/DOA_posts contains a CSV file of text posted during 2013-2013 on the [Day of Archaeology](http://www.dayofarchaeology.com/) 

/SAA_abstracts contains PDF and text files of abstracts of the [Society of American Archaeology](http://www.saa.org/) annual meetings during 2004-2014

### Licenses:

Text:  CC-BY-4.0 http://creativecommons.org/licenses/by/4.0/

Code: MIT http://opensource.org/licenses/MIT year: 2014, copyright holder: Ben Marwick)

Data: CC0 http://creativecommons.org/publicdomain/zero/1.0/ attribution requested in reuse

### Dependencies:

I used [RStudio](http://www.rstudio.com/products/rstudio/) (0.99.56) on Windows 7. Here is the sessionInfo()

```
R version 3.1.1 (2014-07-10)
Platform: x86_64-w64-mingw32/x64 (64-bit)

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] grid      stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] kfigr_1.0.1         gridExtra_0.9.1     JSTORr_1.0.20140222 quanteda_0.6.0.001 
 [5] data.table_1.9.4    tm_0.6              NLP_0.1-5           reshape2_1.4.0.99  
 [9] scales_0.2.4        ggplot2_1.0.0       rvest_0.1.0.9000    dplyr_0.3.0.2      
[13] plyr_1.8.1          knitr_1.8          

loaded via a namespace (and not attached):
 [1] apcluster_1.3.5      assertthat_0.1       car_2.0-22          
 [4] chron_2.3-45         cluster_1.15.2       colorspace_1.2-4    
 [7] DBI_0.3.1            digest_0.6.4         evaluate_0.5.5      
[10] FactoMineR_1.27      formatR_1.0          ggdendro_0.1-15     
[13] gtable_0.1.2         httr_0.5.0.9000      igraph_0.7.1        
[16] lattice_0.20-29      lda_1.3.2            leaps_2.9           
[19] magrittr_1.0.1       MASS_7.3-33          munsell_0.4.2       
[22] nnet_7.3-8           openNLP_0.2-3        openNLPdata_1.5.3-1 
[25] parallel_3.1.1       proto_0.3-10         Rcpp_0.11.3         
[28] rJava_0.9-6          scatterplot3d_0.3-35 slam_0.1-32         
[31] snowfall_1.84-6      stringr_0.6.2        tools_3.1.1         
[34] XML_3.98-1.1  
```

Other system dependencies identified using `dependencies::needs()` (https://github.com/ropensci/dependencies): 

- pandoc (>= 1.12.3) http://johnmacfarlane.net/pandoc
- libcurl (version 7.14.0 or higher) http://curl.haxx.se

Note that these are external to R and are not bundled with this repository. You'll need to ensure they're installed yourself before executing the Rmarkdown file. Pandoc is installed when RStudio is installed.

### Contact: 

Ben Marwick, Assistant Professor, Department of Anthropology
Denny Hall 117, Box 353100, University of Washington
Seattle, WA 98195-3100 USA 

t. (+1) 206.552.9450   e. bmarwick@uw.edu
f. (+1) 206.543.3285   w. http://faculty.washington.edu/bmarwick/ 



