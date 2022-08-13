---
title: "Dealing_with_non-normal_dists"
output: html_document
date: '2022-08-08'
---




```r
#tt
set.seed(5)
#left skewness 
hist(rbeta(100000,100,1)*10)
```

<img src="dealing_with_non-normal_dists_files/figure-html/unnamed-chunk-1-1.png" width="672" />

```r
#right skewness 
hist(rbeta(100000,1,100)*10)
```

<img src="dealing_with_non-normal_dists_files/figure-html/unnamed-chunk-1-2.png" width="672" />

