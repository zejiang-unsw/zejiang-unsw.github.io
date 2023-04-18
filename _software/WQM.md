---
title: "WQM: Wavelet-based Quantile Mapping"
excerpt: "The open-source software WQM is used for post-processing numerical weather prediction."
collection: software
---
<img src='/images/AtmosphericModelSchematic.png'><br/>

The wavelet-based quantile mapping method is developed for post-processing NWP precipitation forecasts. 

# R package

## Requirements
<pre>
Dependencies:
    MBC,
    wmtsa,
    WaveletComp,
    matrixStats,
    data.table, 
    dplyr, tidyr, ggplot2, 
    splus2R (>= 1.2-0), 
    ifultools (>= 2.0-0)
Suggest:
    stats,
    graphics
</pre>

## Installation

You can install the package via devtools from [GitHub](https://github.com/zejiang-unsw/WQM) with:

``` r
devtools::install_github("zejiang-unsw/WQM", dependencies = TRUE)
```

or download via [figshare](https://doi.org/10.6084/m9.figshare.21903033)


# Citation
Jiang, Z., & Johnson, F. (2023). A New Method for Postprocessing Numerical Weather Predictions Using Quantile Mapping in the Frequency Domain. Monthly Weather Review, in press. doi:https://doi.org/10.1175/MWR-D-22-0217.1


# Code for reproducible results in the paper

Download [link](https://doi.org/10.6084/m9.figshare.21903033)


