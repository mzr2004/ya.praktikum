# Machine learning part 4 - forecasting time series

We use machine learning to forecast demand for taxi services in the upcoming hours based on cyclicality of orders.

## Task debrief
1. We are provided with the set of data for taxi orders in airports area
1. Based on cyclicality we have to forecast demand one step ahead.

## Project flow
_Data preparation:_
1. Decomposing data on `seasonal and trend` with `statsmodels.tsa.seasonal`
1. Splitting data on granular level to get understanding of cyclicality (daily, hourly)
1. Selecting and `creating features` given the task of `time series`: lag, roll, etc.

_Modeling:_
1. Based in simple model of linear regression we define what will be the best lag and roll to predict demand.
1. Training `catboost`, `lgbm`, `random forest` models with parameters defined in previous step

## Some results
1. `Catboost` model performs the best forecasting based on `RMSE` measure
