# Stock Graphing Methods in R
[![R-CMD-check](https://github.com/YOUR_USERNAME/YOUR_REPO/workflows/R-CMD-check/badge.svg)](https://github.com/YOUR_USERNAME/YOUR_REPO/actions)
[![CRAN status](https://www.r-pkg.org/badges/version/ggplot2)](https://cran.r-project.org/package=ggplot2)

Explore advanced visualization techniques for stock market data using R, inspired by [Different Ways to Graph Stock Data In R](https://www.youtube.com/watch?v=2ALx_Nb6_9c). This repo implements methods like calendar heatmaps, correlograms, violin plots, and more for datasets like SPY or AAPL.

## Features
- Pulls real-time stock data via `quantmod`.
- Creates publication-ready plots with `ggplot2` and `PerformanceAnalytics`.
- Handles multiple assets and timeframes (daily, intraday).

## Installation
```r
# Install required packages
install.packages(c("quantmod", "ggplot2", "PerformanceAnalytics", "corrplot", "tidyquant"))

# Load libraries
library(quantmod)
library(ggplot2)
library(PerformanceAnalytics)

