# Taxi Company Analysis

## Project Overview

This analysis represents the third part of our project, which focused on data collection and storage in the Practicum course. Unfortunately, we are unable to present the details of the first two parts in this context.

During the initial phase, we obtained weather data for Chicago from the website https://code.s3.yandex.net/data-analyst-eng/chicago_weather_2017.html. We then proceeded to perform exploratory data analysis using SQL on the Practicum database to extract the necessary data for our analysis.

Having completed these preliminary stages, we now move on to the third phase, which is presented in this Jupyter Notebook.

For this analysis, we assume the role of data analysts working for Zuber, a newly launched ride-sharing company in Chicago. Our objective is to uncover patterns within the available data and gain insights into passenger preferences and the influence of external factors on travel behavior.

Using the provided database, we will examine data from competitors and conduct hypothesis testing to assess the impact of weather conditions on trip frequency.


## Data Description

Here are descriptions of the three datasets we obtained:

1. `project_sql_result_01.csv`: This dataset contains data on the number of trips per company. It includes the following columns:
   - **company_name:** The name of the taxi company.
   - **trips_amount:** The total number of trips for each taxi company on November 15-16, 2017.

2. `project_sql_result_04.csv`: This dataset contains data on the average number of trips ending at different locations in Chicago. It includes the following columns:
   - **dropoff_location_name:** The name of the Chicago area where the trip ended.
   - **average_trips:** The average number of trips ending in each region in November 2017.

3. `project_sql_result_07.csv`: This dataset contains journey data from the Loop to O'Hare International Airport. It includes the following fields:
   - **start_ts:** The pick-up date and time.
   - **weather_conditions:** The weather conditions when the trip starts.
   - **duration_seconds:** The duration of the trip in seconds.
     

## Hypothesis

For the purpose of hypothesis testing, we will assess the following hypotheses:
- H0: The average trip duration from the Loop to O'Hare International Airport remains the same on rainy Saturdays.
- H1: The average trip duration from the Loop to O'Hare International Airport changes on rainy Saturdays.

## Stages

The project will be carried out in the following stages:
- Importing both files
- Exploring the data contents
- Ensuring correct data types
- Identifying the top 10 regions for delivery points
- Creating visualizations of taxi companies and their number of trips, as well as the top 10 regions by number of drop-offs
- Drawing conclusions based on the generated visualizations and explaining the findings
- Conducting hypothesis testing on "The average trip duration from the Loop to O'Hare International Airport changes on rainy Saturdays."


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- SciPy version: 1.10.1
