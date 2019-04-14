Dosing Time
================
MarcDRuben
2019-04-13

## Half-life matters

Relationship between drug half-lives and “successes” in circadian
medicine trials. **CircadianTrials** dataset with details of human
trials of dosing time available in repository.

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

## Including Plots
