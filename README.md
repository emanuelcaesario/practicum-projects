# Telecom Plans ML Model

[Project Notebook](https://github.com/emanuelcaesario/practicum-projects/blob/Project-7-Introduction-to-Machine-Learning/Project%207%20Introduction%20to%20Machine%20Learning.ipynb)

## Project Overview

This project serves as a follow-up to our previous work in Project 4 Statistical Data Analysis. Here, we continue to assist Megaline, a mobile operator, in addressing their concern regarding customers who continue to use outdated packages.

The company wants to develop a model capable of analyzing consumer behavior and providing personalized recommendations for the two new Megaline packages: Smart and Ultra.

The objectives of this project include:

- Analyzing the behavior patterns of Megaline customers who have switched to the latest package.
- Developing machine learning models to study the behavior of these users.
- Utilizing the models to provide suitable package recommendations for customers who have not yet adopted the latest package.

## Data Description

To build this model, we will utilize the preprocessed data available in the `users_behavior.csv` file.

Each observation in the dataset provides monthly behavioral information for a single user, including the following variables:

- `сalls`: the number of calls made by the user
- `minutes`: the total duration of calls in minutes
- `messages`: the number of text messages sent by the user
- `mb_used`: the amount of internet usage traffic in megabytes (MB)
- `is_ultra`: the package subscribed by the user for the current month (Ultra - 1, Smart - 0)
     

## Stages

Having previously conducted statistical data analysis on Megaline customer data in Project 4 Statistical Data Analysis, we will now proceed directly to the modeling stage, assuming that the data preprocessing step has been completed.

The objective of this classification task is to develop a model that can accurately recommend the appropriate package for Megaline customers who have not yet switched to the latest package.

Our goal is to create a model with the highest possible accuracy, with a minimum threshold of 0.75 for accuracy in this project.


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Scikit-learn version: 1.2.2
