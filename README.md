# Financial and Weather Data Analysis
This repository contains R code for analyzing financial time series data (ETF closing prices) and weather data (temperature and rainfall).

## Project Overview
The project performs the following analyses:

- **Financial Data Analysis:**
    - Time series analysis of ETF closing prices.
    - Stationarity testing (ADF test).
    - Time series decomposition (STL).
    - ARIMA modeling for forecasting.
    - Calculation of financial risk metrics (Sharpe Ratio, Standard Deviation).

- **Weather Data Analysis:**
    - Correlation analysis between temperature and rainfall.
    - Linear regression modeling to understand the relationship between temperature and rainfall.

## Data
This project uses two datasets:
1.  `Lotus Gold Com.ETF.csv`: Contains historical data for a Lotus Gold ETF, including closing prices, volume, etc.
2.  `Tehran (Mehrabad Airport).csv`: Contains weather data for Tehran (Mehrabad Airport), including temperature and rainfall.

These datasets are included in the repository.

## Requirements
This project requires the following R packages:

- `tidyverse`
- `lubridate`
- `tseries`
- `forecast`
- `xts`
- `PerformanceAnalytics`

You can install these packages in R using the following command:

```R
install.packages(c("tidyverse", "lubridate", "tseries", "forecast", "xts", "PerformanceAnalytics"))
