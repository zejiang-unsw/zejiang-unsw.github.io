---
title: "WASP: Wavelet System Prediction"
excerpt: "The open-source R package WASP is used for system modeling and prediction."
collection: software
---
<img src='/images/x_z.gif'><br/>

An open-source wavelet tool for improving prediction accuracy for natural system models.

## Requirements

Dependencies:
  waveslim

Suggest:
  zoo,
  fitdistrplus,
  knitr,
  rmarkdown,
  [NPRED](https://github.com/zejiang-unsw/NPRED)


## Installation

You can install the package via devtools from [GitHub](https://github.com/) with:

```r
devtools::install_github("zejiang-unsw/WASP", dependencies = TRUE)
```

## Citation
Jiang, Z., Rashid, M. M., Johnson, F., & Sharma, A. (2020). A wavelet-based tool to modulate variance in predictors: an application to predicting drought anomalies. *Environmental Modelling & Software*, 135, 104907. doi:10.1016/j.envsoft.2020.104907

Jiang, Z., Sharma, A., & Johnson, F. (2020). Refining Predictor Spectral Representation Using Wavelet Theory for Improved Natural System Modeling. *Water Resources Research*, 56(3), e2019WR026962. doi:10.1029/2019WR026962
