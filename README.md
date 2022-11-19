## Prediction of tarffic trends
A Traffic dataset is a collection of continuous data points recorded over time. This is why we call it a "time series" data. 
Auto-Regressive Integrated Moving Average or ARIMA for short,is a time series model that predicts future time series values based on previously observed/historical values.

## Introduction
Traffic prediction is a core component of intelligent transportation systems or ITS for short.
This task is an open challenge due to the nonlinear changes in traffic flow. 
In this repository, we use an Auto ARIMA model that identifies dynamical changes in the traffic forecasting. 
Specifically, we use an auto_arima model to specify best parameters set for ARIMA for best functionality of ARIMA model in traffic prediction.

## Prerequisites
Our code is based on Python3, and we use libraries as follows:
1. numpy
2. pandas
3. sktime
4. pmdarima

## Dataset
We use the dataset introduced in  https://github.com/liyaguang/DCRNN to train and evaluate our ARIMA model.
Remember that the ARIMA model take one time series feature as an input and do some predictions for future. W.R.T. this note we must make a model for each station in this dataset.
I do this for 3 first stations in the dataset due to time consuming. You can train and evaluate model for other stations.
