## STOCK PRICE FORECASTING USING TIME SERIES AND DEEP LEARNING

## Introduction
This project aims to forecast stock prices using real-world financial time series data. Stock price prediction helps investors and analysts understand market trends and make informed decisions. In this project, Apple Inc. stock data is used and multiple models such as Prophet, ARIMA, SARIMA, and a Hybrid Deep Learning model are applied to analyze patterns and predict future prices.

## Objective
The objective of this project is to develop and compare different time series and deep learning models to predict stock prices and evaluate their performance using error metrics and visualizations.

## Data Description

* The dataset contains historical stock price data of Apple Inc.

* The data is collected from an online financial source.

* It consists of daily records with the closing price used for analysis.

* The date column is used as the time index, making it suitable for time series forecasting.

## Data Preprocessing

* The date column is set as the index and only the closing price is selected.

* The dataset is split into training and testing sets.

* The data is scaled using normalization for deep learning models.

* Sliding window sequences are created for multi-step forecasting.

* Differencing and seasonal settings are applied for ARIMA and SARIMA models.

## Exploratory Data Analysis

* The stock price series is plotted to observe overall trends and patterns.

* The data shows long-term trends and short-term fluctuations.

* Visual analysis helps in understanding the need for time series models.

## Model Building

* Prophet model is used to capture trend and seasonality.

* ARIMA model is implemented for classical time series forecasting.

* SARIMA model is used to handle seasonal patterns.

* A Hybrid Deep Learning model combining LSTM and Transformer is built.

* All models are trained using the training dataset and used for forecasting.

## Model Evaluation

* The models are evaluated using MAPE and RMSE metrics.

* Forecasted values are compared with actual stock prices using plots.

* The performance of Prophet, Hybrid DL, ARIMA, and SARIMA models is compared.

* Trend comparison is done to study how different models learn patterns.

## Conclusion

The project shows the use of both traditional and deep learning models for stock forecasting.

Classical models capture general trends, while deep learning captures complex patterns.

Comparing multiple models helps in selecting a better forecasting approach for financial data.
