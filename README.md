# Phone Plan Analysis

[Project Notebook](https://github.com/emanuelcaesario/practicum-projects/blob/Project-4-Statistical-Data-Analysis/Project%204%20Statistical%20Data%20Analysis.ipynb)

## Project Overview

In this project, we performed an analysis of prepaid package plans to determine their revenue potential across various target markets. Additionally, we conducted hypothesis testing utilizing statistical analysis methods.

Megaline, a telecom operator, offers two prepaid packages, Surf and Ultimate. The advertising department aims to optimize the advertising budget by identifying which prepaid plan generates more revenue.

In this analysis, we will examine a sample of 500 Megaline clients and explore their behavior, including their identity, origin, package type, and usage statistics such as the number of calls and messages sent in 2018. By analyzing client behavior, we aim to determine which prepaid package brings in higher revenue for Megaline.

## Data Description

We have obtained five data files for this analysis, each containing different information. Here is a description of each data file:

**megaline_users (user data):**
- user_id: User ID
- first_name: User's first name
- last_name: User's last name
- age: User's age in years
- reg_date: Subscription start date (dd, mm, yy)
- churn_date: Date when the user stopped using the service (if missing, it means the service plan was in use when the data was generated)
- city: City where the user lives
- plan: Name of the phone plan

**megaline_calls (call data):**
- id: Unique ID for each web session
- call_date: Date of the call
- duration: Duration of the call in minutes
- user_id: User ID of the caller

**megaline_messages (SMS data):**
- id: Unique SMS ID
- message_date: Date when the SMS was sent
- user_id: User ID of the sender

**megaline_internet (web session data):**
- id: Unique ID for each web session
- mb_used: Volume of data consumed during the session in megabytes
- session_date: Date of the web session
- user_id: User ID

**megaline_plans (phone package data):**
- plan_name: Phone plan name
- usd_monthly_fee: Monthly fee in US dollars
- minutes_included: Monthly call minute allocation
- messages_included: Monthly SMS allocation
- mb_per_month_included: Monthly data volume allocation in megabytes
- usd_per_minute: Price per minute if the package allocation limit has been exceeded
- usd_per_message: Price per SMS if the package allocation limit has been exceeded
- usd_per_gb: Price per extra gigabyte of data if the package allocation limit has been exceeded (1 GB = 1024 megabytes)

## Hypothesis

We were assigned to test two hypotheses in this analysis, namely:
- The average revenue of Ultimate and Surf phone package users is different.
- The average income of users in the NY-NJ area is different from the income of users from other regions.

## Stages

This project will consist of three phases:

1. Data Pre-processing: In this stage, we will clean and prepare the data for analysis. This includes handling missing values, removing outliers, and transforming the data if necessary.

2. Data Analysis: In the second stage, we will perform exploratory data analysis to gain insights and understand the patterns and trends within the dataset. We will calculate descriptive statistics, visualize the data, and identify any relationships or correlations among variables.

3. Hypothesis Testing: The third stage involves conducting hypothesis tests to evaluate specific hypotheses and draw conclusions based on statistical evidence. We will define our null and alternative hypotheses, select an appropriate statistical test, calculate the test statistic, and interpret the results to make informed decisions.

By completing these three phases, we will gain a comprehensive understanding of the prepaid package plans and their revenue potential in different target markets.

## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- SciPy version: 1.10.1
