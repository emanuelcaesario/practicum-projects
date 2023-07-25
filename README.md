# Car Price Model

## Project Overview

Our task involves assisting Rusty Bargain, a company engaged in buying and selling used cars, with the development of an app to attract new buyers. The app will enable users who wish to sell their cars to swiftly ascertain their market value.

To achieve this, we have access to historical data, technical specifications of various vehicles, different model versions, and their corresponding prices. Our primary objective is to create a model that accurately predicts the market value of these cars.

Key factors of interest to Rusty Bargain include:
- the prediction quality
- the speed of the prediction model
- the time required for model training

## Data Description

The datasets are stored in the file `car_data.csv`.

**Features**
- `DateCrawled`: The date when the profile was downloaded from the database.
- `VehicleType`: Vehicle body type.
- `RegistrationYear`: Vehicle registration year.
- `Gearbox`: Gearbox type.
- `Power`: Power of the vehicle (in horsepower).
- `Model`: Vehicle model.
- `Mileage`: Distance traveled by the vehicle (measured in kilometers based on certain regional datasets).
- `RegistrationMonth`: Month of vehicle registration.
- `FuelType`: Fuel type used by the vehicle.
- `Brand`: Vehicle brand.
- `NotRepaired`: Indicates whether the vehicle has been repaired before.
- `DateCreated`: Profile creation date.
- `NumberOfPictures`: Number of vehicle images available.
- `PostalCode`: Postal code of the profile owner (user).
- `LastSeen`: The date of the user's last activity.

**Target**
- `Price`: Price of the vehicle (in Euros).
     

## Stages

The project will encompass several stages:

1. Data Collection:
   - Gather historical data about used cars from various sources.
   - Collect data on vehicle technical specifications, model versions, and prices.
   - Store the obtained data in the file `/datasets/car_data.csv`.

2. Data Analysis:
   - Explore the characteristics and structure of the data to gain insights into the dataset.
   - Identify irrelevant features that can be removed.
   - Address issues related to zero values and outliers in certain columns.
   - Remove duplicate data and fill missing values with 'unknown'.

3. Data Preprocessing:
   - Prepare two datasets: `df` and `df_new` for different modeling needs.
   - Encode categorical features using one-hot-encoding for the `df` dataset.
   - Perform feature scaling to standardize the numerical features.

4. Model Selection and Training:
   - Train and evaluate several machine learning models, including Linear Regression, Decision Tree Regressor, Random Forest Regressor, XGBoost Regressor, LightGBM Regressor, and CatBoost Regressor.
   - Use cross-validation techniques for model evaluation.
   - Tune hyperparameters for the models using RandomizedSearchCV to find the best parameters for each model.

5. Model Evaluation:
   - Compare the performance of each model based on RMSE (Root Mean Squared Error) scores and training times.
   - Identify the best model that strikes a balance between prediction accuracy and training speed.

6. Conclusion:
   - Summarize the findings and observations from the model evaluations.
   - Recommend the most suitable model (CatBoost Regressor) for Rusty Bargain based on the criteria of prediction quality, speed, and training time.

## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Scikit-learn version: 1.2.2
- CatBoost version: 1.1.1
- LightGBM version: 3.3.5
- XGBoost version: 1.7.3
