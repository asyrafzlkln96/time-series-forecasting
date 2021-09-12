# Time-series-forecasting
Time Series Forecasting

## 1. What is Time series Model?
* Time series are series of data points listed in time order
* Time series forecasting is the use of a model to predict future values based on previously observed values

## Process:
* Similar with Machine Learning process but the inputs are limited to 2, i.e : ds (datetime[ns] and y-value)

## 2. Time Series Analysis Methods
For this repo, I'm going to demonstrate 4 Time Series Methods. Actually there are more methods to explore, will update this repo later on.

* Autoregressive Integrated Moving Average (ARIMA)
* Auto ARIMA
* Prophet
* Regresssion
* Vector Autoregression (VAR) : To deal with Multivariate Time Analysis

## 3. Multivariate Time Analysis
Multivariate Time Analysis is used when we have more than one dependent variable for time series.
The most commonly used methods for multivariate time series forecasting – Vector Auto Regression (VAR).

In a VAR model, each variable is a linear function of the past values of itself and the past values of all the other variable.
