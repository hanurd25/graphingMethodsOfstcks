# Stock Graphing Methods in R

Exploring visualization techniques for stocks using R, inspired by [Different Ways to Graph Stock Data In R](https://www.youtube.com/watch?v=2ALx_Nb6_9c). 

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

