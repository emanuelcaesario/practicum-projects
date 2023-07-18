# Bank Customer Churn Prediction

## Project Overview

Bank Beta has been experiencing a decline in customer numbers over time, highlighting the importance of retaining existing customers rather than acquiring new ones. To address this challenge, the bank is seeking accurate prediction models to anticipate customer behavior and proactively mitigate customer churn. By identifying customers with a higher likelihood of leaving the bank, strategic measures can be taken to retain them.

Our objective is to predict the likelihood of customer churn in the banking industry. By utilizing historical data on client behavior and contract terminations, we aim to develop a model that can accurately determine whether a customer is likely to leave the bank in the near future.

The primary goal is to achieve a high F1 score of at least 0.59 on the test dataset. Additionally, we will evaluate the model's performance using the AUC-ROC metric and compare it with the F1 scores to gain further insights.

## Data Description

For machine learning training, we will be using the dataset stored in the file `Churn.csv`. This dataset contains the following features and target variable:

**Features:**
- `RowNumber`: Index of the data string
- `CustomerId`: Customer ID
- `Surname`: Last name
- `CreditScore`: Credit score
- `Geography`: Country of residence
- `Gender`: Gender
- `Age`: Age
- `Tenure`: Maturity period for customer fixed deposits (in years)
- `Balance`: Account balance
- `NumOfProducts`: Number of bank products used by the customer
- `HasCrCard`: Whether the customer has a credit card
- `IsActiveMember`: Level of customer activity
- `EstimatedSalary`: Estimated salary

**Target:**
- `Exited`: Whether the customer has quit
     

## Stages

The project will encompass several stages:

1. Data pre-processing: Downloading and preparing the data for analysis.
2. Class balance check: Assessing the distribution of existing classes.
3. Model training without considering class imbalance: Training the initial model and analyzing the obtained results.
4. Improving model performance by addressing class imbalance: Implementing techniques to address the class imbalance issue.
5. Parameter selection using the training set: Fine-tuning the model's parameters based on the training set.
6. Training and evaluating different models on the training and validation sets: Experimenting with various models and assessing their performance.
7. Identifying the best models: Selecting the models with the highest performance.
8. Conducting final tests: Running tests on the selected models to assess their effectiveness.


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Scikit-learn version: 1.2.2
