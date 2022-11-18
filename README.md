## Traffic prediction using ARIMA model
Traffic data is a set of continuous data points recorded over time. so we call this data as "time series" data. 
Auto-Regressive Integrated Moving Average or ARIMA for short, is a time series model because it identifies some patterns in data and make some predictions for future based on these patterns.

## Introduction
Traffic prediction is a core component of intelligent transportation systems or ITS for short.
This task is an open challenge due to the nonlinear changes in traffic flow. 
In this repository, we use an Auto ARIMA model that identifies dynamical changes in traffic forecasting. 
Specifically, we use an auto_arima model to specify best parameters set for ARIMA for best functionality of ARIMA model in traffic prediction.

## Prerequisites
Our code is based on Python3, and we use libraries as follows:
1. numpy
2. pandas
3. sktime
4. pmdarima

## Dataset
We used the dataset introduced in  https://github.com/liyaguang/DCRNN to train and evaluate our ARIMA model.
Remember that the ARIMA model take one time series feature as an input and do some predictions for this future. W.R.T. this note we must set a model for each station in this dataset.
Because of time consuming this task, we do this for 3 first station in dataset. You can train and evaluate model for other stations like these stations.
