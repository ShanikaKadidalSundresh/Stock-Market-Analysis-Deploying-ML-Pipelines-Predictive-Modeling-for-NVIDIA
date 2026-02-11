README
================

# Stock Market Analysis Deploying ML Pipelines: Predictive Modeling for NVIDIA

------------------------------------------------------------------------

## Project Overview

This project analyzes historical **NVIDIA (NVDA)** stock data
(1999–2024) and develops multiple statistical and machine learning
models to forecast future stock prices.

The goal is to compare traditional time-series methods with machine
learning approaches and benchmark performance using RMSE.

------------------------------------------------------------------------

## Key Features

- Data Cleaning & Preprocessing  
- Feature Engineering (Technical Indicators)  
- Exploratory Data Analysis (EDA)  
- Machine Learning & Time-Series Modeling  
- Model Performance Benchmarking  
- 30-Day Forecast Comparison

------------------------------------------------------------------------

## Models Implemented

| Model                        | Type           | Purpose                      |
|------------------------------|----------------|------------------------------|
| Linear Regression            | Statistical    | Baseline prediction          |
| Ridge Regression             | Regularized ML | Reduce overfitting           |
| Random Forest                | Ensemble ML    | Non-linear modeling          |
| Support Vector Machine (SVM) | ML             | High-dimensional regression  |
| ARIMA                        | Time Series    | Trend & seasonality modeling |

------------------------------------------------------------------------

## Technical Indicators Used

- Moving Average (MA20)  
- Relative Strength Index (RSI)  
- Bollinger Bands  
- Rolling Volatility  
- Trend & Seasonality Components

------------------------------------------------------------------------

## Model Evaluation

All models were evaluated using:

- RMSE (Root Mean Squared Error)  
- Train/Test Split  
- Forecast Comparison

Final model selection was based on lowest forecasting error.

------------------------------------------------------------------------

## How to Run

1.  Clone the repository

2.  Open the `.Rproj` file in RStudio.

3.  Install required packages:

``` r
install.packages(c(
  "readxl",
  "dplyr",
  "ggplot2",
  "caret",
  "forecast",
  "TTR",
  "randomForest",
  "glmnet",
  "corrplot",
  "e1071"
))
```

4.  Run the main script to reproduce results.

------------------------------------------------------------------------

## Tech Stack

- R  
- caret  
- forecast  
- randomForest  
- glmnet  
- e1071  
- ggplot2

------------------------------------------------------------------------

## Skills Demonstrated

- Time Series Forecasting  
- Machine Learning in R  
- Financial Data Modeling  
- Feature Engineering  
- Performance Benchmarking  
- Data Visualization

------------------------------------------------------------------------
