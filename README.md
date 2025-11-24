# Vector Autoregression (VAR) Forecasting Model

This repository contains a Python implementation of a Vector Autoregression (VAR) model using `statsmodels`. It demonstrates how to model, analyze, and forecast multivariate time series data where variables influence each other over time.

## 📌 Overview

Vector Autoregression is a stochastic process model used to capture the linear interdependencies among multiple time series. Unlike univariate models (like ARIMA) which look at a single variable, this VAR model analyzes the relationship between two correlated variables (`Series_A` and `Series_B`) to predict future movement based on past values of both.

## 🛠 Dependencies

To run this project, you will need the following Python libraries:

```bash
pip install pandas numpy matplotlib statsmodels
