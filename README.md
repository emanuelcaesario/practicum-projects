# Taxi Orders Prediction Model

## Project Description

We work for a taxi company called Sweet Lift, which has collected historical data about taxi orders at the airport. Our task is to predict the number of taxi orders for the next hour to attract more drivers during rush hour. The goal is to build a predictive model with an RMSE metric on the test set not exceeding 48.

This project aims to:
- Apply time series data processing skills to real-world projects.
- Analyze data characteristics to identify patterns, trends, and seasonality.
- Create several models for making predictions.
- Choose and recommend the best model for implementation.


## Data Description

The data is stored in the `taxi.csv` file, with the number of orders represented in the `num_orders` column.
- `datetime`— contains the date and time sequence of data retrieval.
- `num_orders`— represents the number of taxi orders per unit of time.


## 1.4 Stages

This project will be completed in the following stages:
- Importing files and formatting the data for time series analysis.
- Studying the general information of the data and ensuring data quality.
- Conducting data analysis to understand its characteristics.
- Creating a precise predictive model.
- Testing the model on a separate test dataset.
- Drawing conclusions and selecting the best model for implementation.


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- Scikit-learn version: 1.2.2
- CatBoost version: 1.1.1
- LightGBM version: 3.3.5
- XGBoost version: 1.7.3
- Statsmodels version: 0.13.5
- Scipy version: 1.10.1
- Pmdarima version: 1.8.5
- Prophet version: 1.0
