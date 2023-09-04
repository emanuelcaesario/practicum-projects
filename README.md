# Borrower's Default Risk

[Project Notebook](https://github.com/emanuelcaesario/practicum-projects/blob/Project-2-Data-Pre-processing/Proyek%202%20Data%20Pre-processing%20-%20English.ipynb)

## Project Overview

This project aims to showcase my data pre-processing skills. The data pre-processing tasks involve cleaning and organizing the data to ensure its accuracy and suitability for analysis.

The objective of this project is to prepare a report for the credit department of a bank, analyzing the impact of a customer's marital status and the number of children on the likelihood of loan default. The insights from this report will be used in credit assessments for potential customers, helping in the evaluation of their creditworthiness and repayment capacity.


## Data Description

The dataset provided by the bank contains various columns with relevant information as follows:

- `children` - the number of children in the family
- `days_employed` - customer's work experience in days
- `dob_years` - customer's age in years
- `education` - level of customer education
- `education_id` - identifier for the customer's education level
- `family_status` - identifier for the customer's marital status
- `family_status_id` - identifier of marital status
- `gender` - the customer's gender
- `income_type` - type of work
- `debt` - whether the customer has a loan payment debt
- `total_income` - monthly income
- `purpose` - the purpose of getting a loan

## Stages

This project is divided into several stages, which are as follows:

### Stage 1: Reading and Understanding the Data
In this stage, I thoroughly examine the dataset to gain a comprehensive understanding of its quality, structure, and potential issues. This initial exploration helps identify any data-related challenges that need to be addressed before proceeding with further analysis.

### Stage 2: Data Pre-processing
This stage forms the core of the project and focuses on resolving the issues identified in the previous stage. The key steps involved in data pre-processing are as follows:
- Identifying and filling in missing values: I employ appropriate techniques to handle missing values in the dataset, ensuring that the data is complete and suitable for analysis.
- Converting real number data types to integer types: I adjust the data types of relevant columns to accurately represent the data and facilitate subsequent calculations or analysis.
- Removing duplicate data: I identify and remove any duplicate entries in the dataset to ensure data integrity and prevent potential distortions in the analysis.
- Categorizing data: I group and categorize data based on specific criteria, simplifying complex information and enabling easier analysis and interpretation.

### Stage 3: Hypothesis Analysis
In this stage, I address the research questions posed in the assignment:

- Relationship between having children and loan default probability: I examine the correlation between the number of children a customer has and the likelihood of defaulting on a loan.
- Relationship between marital status and loan default probability: I analyze the impact of marital status on the probability of loan default, exploring any potential connections or patterns.
- Relationship between income level and loan default probability: I investigate how different income levels influence the likelihood of defaulting on a loan, examining any associations between income and loan repayment capacity.
- Impact of loan objectives on loan default probability: I explore the effect of different loan purposes (such as buying a car, education, housing, etc.) on the probability of default, identifying any significant trends or patterns.

### Stage 4: Writing the General Conclusion
In this final stage, I summarize the findings from the entire project, presenting a comprehensive conclusion based on the data analysis and hypothesis testing. This conclusion serves as a comprehensive summary of the insights gained and their implications for the bank's credit assessment processes.

By following this structured approach, I aim to effectively process and analyze the provided dataset, providing valuable insights and recommendations for the credit department based on the correlations and patterns observed in the data.

## Libraries
- Pandas version: 1.4.4
- Numpy version: 1.23.5
- Seaborn version: 0.12.2
