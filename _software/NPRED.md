---
title: "Predictor identifier: Nonparametric PREDiction (NPRED)"
excerpt: "The open-source R package NPRED is used to identify the meaningful predictors to the response from a large set of potential predictors."
collection: software
---
<img src='/images/mi.png'><br/>

A new version based on [NPRED](http://hydrology.unsw.edu.au/download/software/NPRED) without calling Fortran codes.

## Requirements
<pre>
Dependencies:
	stats
	
Suggests: 
    zoo, SPEI,
    WASP, synthesis,
    testthat, devtools
</pre>

## Installation
You can install the package via devtools from [GitHub](https://github.com/zejiang-unsw/NPRED) with:

```r
devtools::install_github("zejiang-unsw/NPRED")
```

or via [CRAN](https://cran.r-project.org/web/packages/NPRED/index.html) with: 

``` r
install.packages("NPRED")
```

## Citations
Sharma, A., & Mehrotra, R. (2014). An information theoretic alternative to model a natural system using observational information alone. *Water Resources Research*, 50(1): 650-660.

Galelli S., Humphrey G.B., Maier H.R., Castelletti A., Dandy G.C. & Gibbs M.S. (2014). An evaluation framework for input variable selection algorithms for environmental data-driven models, *Environmental Modelling & Software*, 62, 33-51.

Sharma, A., Mehrotra, R., Li, J., & Jha, S. (2016). A programming tool for nonparametric system prediction using Partial Informational Correlation and Partial Weights. *Environmental Modelling & Software*, 83, 271-275.

Mehrotra, R., & Sharma, A. (2006). Conditional resampling of hydrologic time series using multiple predictor variables: A K-nearest neighbour approach. *Advances in Water Resources*, 29(7), 987-999.
