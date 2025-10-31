Econometric Analysis of Crude Oil Prices and Inflation in India
Overview

This project explores the relationship between crude oil prices and inflation in India using econometric techniques in Python. The analysis involves time-series visualization, Ordinary Least Squares (OLS) regression, and autocorrelation testing to understand how oil price fluctuations influence inflationary trends.

The project was developed and executed in Google Colab, with data imported from an Excel file (eviews data.xlsx).

Objectives

Examine the impact of crude oil prices on inflation in India.

Perform OLS regression to quantify the relationship between the two variables.

Conduct autocorrelation testing to verify the time-series dependency of residuals.

Visualize the trend and volatility of crude oil prices over time.

Methodology

Data Import & Preprocessing

Dataset imported from Excel into Google Colab using pandas.

Date column converted to datetime format and set as index.

Exploratory Visualization

Time-series plot of crude oil prices using matplotlib.

Trend analysis from 2000–2016.

Econometric Analysis

OLS regression performed using statsmodels to estimate how oil prices affect inflation.

Autocorrelation test (Durbin-Watson statistic) applied to check serial correlation in residuals.

Key Findings

Crude oil prices showed significant variation over the period 2000–2016.

Regression analysis indicated a positive relationship between oil prices and inflation.

Durbin-Watson test confirmed minimal autocorrelation in residuals, validating model reliability.
