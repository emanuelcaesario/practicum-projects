# Final Project: Predicting Telco Churn Rate

## Project Structure

This final project is part of a data science course at Practicum, where we apply everything we have learned throughout the bootcamp in a real-world simulation. Unlike previous projects, this final project simulates real work situations in companies. We engage in role play simulations, with the tutoring team playing the roles of our colleagues:

- Tutor 1 acts as the team leader, assigning tasks and ensuring their successful completion.
- Tutor 2 serves as the senior co-worker, providing answers to common machine learning questions and offering help when needed.
- Code reviewers assess our code.

**Task Details:**

1. **Create a Work Plan**
   - Study the provided tasks and seek clarification from the team leader if needed.
   - Develop a work plan and conduct exploratory data analysis (EDA).
   - Create a list of questions requiring clarification and outline a rough plan at the end of the Jupyter Notebook, defining 3-5 basic steps and explaining each step in one or two sentences.
   - The team leader will review the questions and work plan, providing feedback if any doubts are found.
   - The EDA code will be reviewed by the team leader to ensure its correctness.

2. **Develop Solution Model Code**
   - Develop code to address the problems identified in the approved projects.
   - Ensure the compiled code follows proper steps and is well-executed.
   - Verify that the solution code aligns with the task requirements.
   - Ensure the machine learning model created meets the targeted quality score.
   - Send the code to the project reviewer for assessment.

3. **Create a Task Report**
   - Prepare a report documenting the steps taken during the project, along with the results and recommendations.
   - Address the following questions in the report:
     - What steps have you taken, and which ones have you skipped? Explain the reasons behind your decisions.
     - What challenges did you encounter, and how did you overcome them?
     - Outline the key steps taken to complete the task.
     - Describe your final model and its quality score.
   - Submit the report to the team leader for review to ensure proper completion of the task.
   - The team leader will consider factors such as the completeness and clarity of our answers in the evaluation.
   - The final score is highly dependent on the quality of our models.
   - To be successful, we need to achieve five story points (SP). Story points (SP) are used to measure the difficulty level of a task, and we can earn 4 - 6 SP for the main project and 1 SP for additional tasks.
  

## Project Description

A telecommunications operator named Interconnect wants to predict the churn rate of their clients. If it is known that a client is planning to quit, they will be offered promotional codes and special package options. Interconnect's marketing team has collected some personal data from clients, including information about data plans selected and their contracts.

**Interconnect Services**

Interconnect provides two main types of services:

1. Landline network: Phones can be connected to multiple channels simultaneously.
2. Internet: Internet networks can be managed via telephone lines (DSL, digital subscriber line) or via fiber optic cables.

Some of the other services that Interconnect provides include:

- Internet security: antivirus software (DeviceProtection) and malicious website blocker (OnlineSecurity)
- Dedicated technical support line (TechSupport)
- Cloud storage for files and backup data (OnlineBackup)
- Streaming TV (StreamingTV) and movie directories (StreamingMovies)

Clients can choose to pay monthly or sign a contract for a 1 or 2-year subscription. They can use various payment methods and receive electronic bills after transactions.


## Data Description

The available data consists of four files obtained from different sources:

- `contract.csv` — containing contract information
- `personal.csv` — containing client personal data
- `internet.csv` — containing information about Internet services
- `phone.csv` — containing information about phone services

Each file includes a `customerID` column with a unique code assigned to each client.

The contract information is up to date as of February 1, 2020.


## Project Goals

This project has three main objectives:

- Analyze the provided data to identify factors that can influence the churn rate of customers.
- Develop machine learning models that can efficiently predict the likelihood of customers leaving Interconnect services.
- Generate relevant promotional recommendations to mitigate customer churn and retain their loyalty to the service.


## Stages of Project Completion

This project will be carried out in four phases:

1. Data pre-processing: Enhance data quality to facilitate more effective analysis.
2. Exploratory data analysis: Investigate the factors influencing customer churn rate.
3. Machine learning modeling: Develop a machine learning model capable of accurately predicting churn rate.
4. Final report and recommendations: Summarize the project implementation and propose appropriate promotion strategies based on the key factors contributing to customer churn in Interconnect services.

## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- RegEx version: 2.2.1
- Scikit-learn version: 1.2.2
- SciPy version: 1.10.1
- LightGBM version: 3.3.5
- XGBoost version: 1.7.3
- CatBoost version: 1.1.1
