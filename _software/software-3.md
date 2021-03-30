---
title: "synthesis: Generate Synthetic Data from Statistical Models"
excerpt: "Generate synthetic time series from commonly used statistical models, including linear, nonlinear and chaotic systems.<br/><img src='/images/synthesis.png'>"
collection: software
---

## Requirements
<pre>
Dependencies:
  stats, MASS

Suggest:
  testthat, devtools
</pre>

## Installation

You can install the package via [CRAN](http://cran.r-project.org/) with: 

``` r
install.packages("synthesis")
```

or via devtools from [GitHub](https://github.com/) for the development version:

``` r
devtools::install_github("zejiang-unsw/synthesis")
```

## Citation
Jiang, Z., Rashid, M. M., Johnson, F., & Sharma, A. (2020). A wavelet-based tool to modulate variance in predictors: an application to predicting drought anomalies. Environmental Modelling & Software, 135, 104907. https://doi.org/10.1016/j.envsoft.2020.104907

Jiang, Z., Sharma, A., & Johnson, F. (2020). Refining Predictor Spectral Representation Using Wavelet Theory for Improved Natural System Modeling. Water Resources Research, 56(3), e2019WR026962. doi:https://doi.org/10.1029/2019WR026962

Galelli, S., et al. (2014). "An evaluation framework for input variable selection algorithms for environmental data-driven models." Environmental Modelling and Software 62: 33-51.
	
Sharma, A. (2000). "Seasonal to interannual rainfall probabilistic forecasts for improved water supply management: Part 1 — A strategy for system predictor identification." Journal of Hydrology 239(1): 232-239.
