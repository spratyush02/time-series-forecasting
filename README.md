# Data Science pipeline for prediction of Coal Prices.

We provide **project report file** to understand our extensive EDA, Research Questions and methodologies. The notebook is very well **commented** to understand everything required to run this project.

Highlights:

1) Extensive EDA
2) Feature Selection and Extraction
3) ARIMA Model Trained
4) XGBRegressor (ML) trained
5) LSTM (DL) trained
6) Hyperparameter tuning using TALOS

# Introduction

In this project, we analysed the timeseries for the forecasting of Coal prices in South Africa. We did extensive 'Exploratory Data Analysis' with the help of which we performed data cleaning, processing along with feature selection and extraction. We checked the timeseries for stationarity and seasonality using both graphical and mathematical models. We handled outliers in some years. We believe the reason for the outliers is the economic crisis in 2008. There was a sharp slowdown in demand, and with mining output remaining stubbornly high. Therefore, coal benchmarks fell down.  We trained Classical timeseries forecasting method: ARIMA (Auto Regressive Integrated Moving Average), and a Deep Learning method using LSTM along with extensive hyperparameter search using TALOS library.  

We calculate the metric R^2 (coefficient of determination) regression score function. The R^2 score obtained using ARIMA is 0.96 in comparison to 0.61 which is achieved by LSTM model. For this, not very complex, timeseries ARIMA outperforms the LSTM model as we are trying an overly complex Deep Learning method to fit on a simple timeseries data.

We have two notebooks:

1) project.ipynb -  For ARIMA and LSTM model
2) ML.ipynb - for Machine Learning model


Thank you
