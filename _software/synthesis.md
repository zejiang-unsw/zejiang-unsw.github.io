---
title: "synthesis: Generate Synthetic Data from Statistical Models"
excerpt: "Generate synthetic time series from commonly used statistical models, including linear, nonlinear and chaotic systems."
collection: software
---
<img src='/images/synthesis.png'><br/>

An open-source tool for generating synthetic data from statistical models.

## Requirements
<pre>
Dependencies:
	stats, MASS

Suggest:
	testthat, devtools
</pre>

## Installation

You can install the package via [CRAN](https://cran.r-project.org/web/packages/synthesis/index.html) with: 

``` r
install.packages("synthesis")
```

or via devtools from [GitHub](https://github.com/zejiang-unsw/synthesis) for the development version:

``` r
devtools::install_github("zejiang-unsw/synthesis")
```

## Citation
Jiang, Z., Rashid, M. M., Johnson, F., & Sharma, A. (2020). A wavelet-based tool to modulate variance in predictors: An application to predicting drought anomalies. Environmental modelling & software, 135, 104907.

Jiang, Z., Sharma, A., & Johnson, F. (2020). Refining Predictor Spectral Representation Using Wavelet Theory for Improved Natural System Modeling. Water Resources Research, 56(3), e2019WR026962.

Jiang, Z., Sharma, A., & Johnson, F. (2019). Assessing the sensitivity of hydro-climatological change detection methods to model uncertainty and bias. Advances in Water Resources, 134, 103430.

Galelli, S., Humphrey, G. B., Maier, H. R., Castelletti, A., Dandy, G. C., & Gibbs, M. S. (2014). An evaluation framework for input variable selection algorithms for environmental data-driven models. Environmental modelling & software, 62, 33-51.

Sharma, A. (2000). Seasonal to interannual rainfall probabilistic forecasts for improved water supply management: Part 1 - A strategy for system predictor identification. Journal of Hydrology, 239(1), 232-239. 
