# Bitcoin Daily Price Forecasting Using Time Series Analysis

## Introduction
Bitcoin's volatile market makes it an interesting subject for time series analysis. This project explores the daily price fluctuations of Bitcoin and applies different forecasting models to predict future prices. The goal is to understand and compare the performance of linear and non-linear regression models, as well as ARIMA, for time series forecasting.

## Objectives
- Manipulate and prepare time series data for analysis.
- Build and compare different time series forecasting models.
- Evaluate and interpret the results to determine the most suitable model for forecasting Bitcoin daily prices.

## Data Set
The data set includes CSV files for the daily prices of Bitcoin (`BTC-Daily.csv`). Each entry in the dataset contains a date and a daily closing price.

## Assignment Tasks

### Part 1: Data Exploration and Preparation
- **Data Loading**: Import the `BTC-Daily.csv` file into a data analysis tool (`pandas`).
- **Initial Exploration**:
  - Describe the dataset, including the range of dates covered and the statistics of the closing prices.
  - Visualize the daily closing prices using line plots.
- **Preprocessing**:
  - Check for and handle any missing or anomalous data.
  - Normalize or standardize the prices if necessary for modeling.

### Part 2: Building Forecasting Models
- **Linear Regression**:
  - Use the dates as numerical features to perform a simple linear regression.
  - Discuss the appropriateness of a linear model for this kind of data.
- **Non-Linear Regression**:
  - Explore a non-linear model and justify the choice of the specific model.
  - Include non-linear transformations or polynomial features as predictors.
- **ARIMA Model**:
  - Test for stationarity and perform differencing if needed.
  - Determine the order of the ARIMA model by analyzing ACF and PACF plots.
  - Fit the ARIMA model to the data and interpret the model summary.

### Part 3: Model Evaluation and Selection
- **Performance Metrics**: Calculate RMSE (Root Mean Square Error), MAE (Mean Absolute Error), and MAPE (Mean Absolute Percentage Error) for each model.
- **Cross-Validation**: Employ time series cross-validation techniques to evaluate the models' forecasting performance.
- **Residual Analysis**: Analyze the residuals from each model to check for any patterns or systematic errors.

### Part 4: Comparative Analysis and Conclusion
- **Comparative Discussion**: Discuss the strengths and weaknesses of each model for this dataset based on the calculated performance metrics and residual analysis.
- **Best Model Justification**: Identify which model performed the best and provide reasoning based on the results of the analysis.
- **Conclusion**: Summarize the findings, discussing the challenges encountered in forecasting Bitcoin daily prices and the insights gained from using different models.

## Conclusion
This project aims to provide a comprehensive analysis of different forecasting models for predicting Bitcoin daily prices, offering insights into their performance and applicability for time series data.
