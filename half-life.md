Dosing Time
================
MarcDRuben
2019-04-14

## Half-life matters

Relationship between drug half-lives and “successes” in circadian
trials. Dataset named **CircadianTrials** contains details of more than
100 human trials of dosing time. Available in this repo.

``` r
head(CircadianTrials[, 1:4])
```

    ## # A tibble: 6 x 4
    ##    year drug                 halflife.hr therapeutic.area                  
    ##   <dbl> <chr>                      <dbl> <chr>                             
    ## 1  1997 oxaliplatin, fluoro…         0.5 colorectal cancer                 
    ## 2  1990 oxaliplatin                  0.5 mixed cancers (breast carcinoma, …
    ## 3  1994 oxaliplatin, fluoro…         0.5 colorectal cancer                 
    ## 4  2000 granulocyte-macroph…        NA   soft tissue or bone sarcoma       
    ## 5  2006 oxaliplatin, fluoro…         0.5 colorectal cancer                 
    ## 6  2009 radiotherapy                NA   head and neck cancer

![](half-life_files/figure-gfm/plot-1.png)<!-- -->
