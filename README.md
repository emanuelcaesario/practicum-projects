# Oil Well Location Analysis

## Project Overview

OilyGiant, an oil mining company, aims to expand its exploration to new locations. Our task is to find a suitable location for drilling a new oil well. To accomplish this, we will develop a machine learning model that can help identify the right location for further exploration.

We have been provided with oil sample data from three regions, including parameters for each oil well in those areas. Our objective is to build a model that can assist the company in selecting the region with the highest profit margin. To achieve this, we will conduct an analysis of potential profits and risks using bootstrapping techniques.

The following steps will guide us in selecting the new location:

1. Gather parameters related to oil quality and volume of oil reserves for the selected areas.
2. Develop a model capable of predicting the volume of oil reserves in new wells.
3. Determine the oil well with the highest estimated value.
4. Choose the region that offers the highest total profit based on the selected oil wells.

The objective of this project is to identify new oil extraction locations that offer the highest profit margins for the company.


## Data Description

The data provided for this project consists of artificial data, without specific contract details or well characteristics. The geological exploration data for the three areas are stored in separate files: 
- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`.

Features:
- `id` - unique ID of the oil well
- `f0`, `f1`, `f2` - three dot features (specific meaning is not important, but the features themselves are significant)

Target:
- `product` - volume of oil reserves in the well (measured in thousands of barrels)

Conditions:
- Only linear regression is suitable for model training, as other models are insufficient for prediction.
- During the region exploration, 500 points are studied and the best 200 points are selected for profit calculation.
- The budget for developing 200 oil wells is 100 million USD.
- Revenue from one barrel of raw materials is 4.5 USD. Thus, the revenue from one unit of product (volume of oil reserves in thousands of barrels) is 4500 dollars.
- After assessing the risks, only areas with a risk of loss lower than 2.5% are considered. From the eligible regions, the one with the highest average profit is selected.
 

## Stages

This project will involve several stages, including:
- Data preparation
- Training and testing models for each region
- Setting up calculations for profit estimation
- Developing a function to calculate profits based on selected oil wells and model predictions
- Evaluating the risks and potential profits for each region


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- Scikit-learn version: 1.2.2
