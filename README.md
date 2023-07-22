# Machine Learning Solutions for Insurance

## Project Overview

This project showcases the practical applications of linear algebra, combining its mathematical beauty with real-world tasks. The main objective is to demonstrate the accuracy of our algorithm rather than selecting the best model. The project template includes initial code and task descriptions, which will not be removed, along with two appendices providing useful information.

In this project, an insurance company called "Sure Tomorrow" seeks machine learning solutions for various tasks:

- Task 1: Client profiling - Find clients similar to specific criteria for effective marketing.
- Task 2: Claim prediction - Determine if new clients are likely to make insurance claims and compare model predictions with a dummy model.
- Task 3: Regression - Predict the amount of insurance claims new clients may receive using linear regression.
- Task 4: Data Privacy Protection - Develop data transformation algorithms to obfuscate or hide the client's private information while maintaining the accuracy and quality of the machine learning model. The goal is to prevent misuse or unauthorized access to clients' personal data, ensuring data privacy is maintained without compromising the performance of the machine learning model.

## Data Description

The dataset is available in the `insurance_us.csv` file. Here are the description of the data:

- Features:
  - Gender: The gender of the insured (e.g., male or female).
  - Age: The age of the insured in years (numeric value).
  - Income: The income of the insured (numeric value).
  - Family Members: The number of family members covered by the insurance.
  
- Target variable:
  - Insurance Benefits: The amount of insurance claims received by the insured during the last five years. This represents the benefits or claims the insured has received from the insurance company.
     

## Stages

The project will encompass several stages:

1. **Data Loading and Initialization:**
   - Load the dataset from the `insurance_us.csv` file.
   - Explore the dataset to understand its structure and contents.
   - Check for missing values, data types, and basic statistics.
   

2. **EDA (Exploratory Data Analysis):**
   - Perform exploratory analysis to understand the relationships between features and the target variable (insurance_benefits).
   - Identify patterns or correlations in the data through visualization.
   

3. **Task 1 - Similar Clients:**
   - Create a function to display k-nearest neighbors for the nth object based on a specific distance metric.
   

4. **Task 2 - Insurance Claim Prediction:**
   - Evaluate whether the kNN classification model is a better approach than the dummy model for predicting insurance claim acceptance.
   

5. **Task 3 - Regression (with Linear Regression):**
   - Using insurance_benefits as the target variable, evaluate the Root Mean Squared Error (RMSE) for the Linear Regression model.
   

6. **Task 4 - Data Obfuscation:**
   - Apply data obfuscation by multiplying numerical features (remember these features are seen in matrix 𝑋) with an invertible matrix 𝑃.
   - Demonstrate the effectiveness of data obfuscation with Linear Regression.
   

7. **Test Linear Regression with Data Obfuscation:**
   - Test the Linear Regression model with obfuscated data to assess its performance and accuracy.

## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Scikit-learn version: 1.2.2
