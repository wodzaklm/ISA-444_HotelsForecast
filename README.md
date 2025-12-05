## Hotel Room Demand Forecast Project
This repository contains the Python notebook 
and relevant documents to the ISA 444 Fall 2025 Final project. 

### Features
* Python notebook including:
    * a 5-fold time=series cross-validation without overlapping windows
    * a plot of forecast values and actual values 
    * a one-month future forecast (plotted)
* Uses 8 different models from StatsForecast, NeuralForecast, and MLForecast:
    * Naive
    * Seasonal Naive
    * AutoETS
    * AutoARIMA
    * AutoNBEATS
    * AutoNHITS
    * XGBRegressor
    * TimeGPT
* Evaluates the cross-validation on:
    * RMSE
    * MAE
    * MAPE
 
## About StatsForecast
StatsForecast is a Python library that provides statistical forecasting algorithms for time series data. It is fast and scalable and offers many classical forecasting methods.

For more information, visit Nixtla's StatsForecast repository.

## About NeuralForecast
NeuralForecast offers a large collection of neural forecasting models focused on usability and robustness. 

For more information, visit: https://nixtlaverse.nixtla.io/neuralforecast/docs/getting-started/introduction.html

## About MLForecast
MLForecast is a framework to perform time series forecasting using machine learning models, with the option to scale to massive amounts of data using remote clusters.

For more information, visit https://nixtlaverse.nixtla.io/mlforecast/index.html

## About TimeGPT
TimeGPT is a foundational model for time series, providing state-of the art forecasting and anomaly detection, designed to improve time series data-driven decision making.

For more information, visit: https://www.nixtla.io/docs
