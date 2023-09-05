# Video Game Analysis

[Project Notebook](https://github.com/emanuelcaesario/practicum-projects/blob/Project-5-Integrated-Project-1/Project%205%20Integrated%20Project%201.ipynb)

## Project Overview

This project is an first integrated project of Practicum courses that encompass various skills taught throughout the first part of the curriculum, including basic Python, data preprocessing, exploratory data analysis, and statistical data analysis.

As data analysts for the online store "Ice," which specializes in selling video games worldwide, we were provided with data from open sources. This data includes expert and user reviews, genres, game platforms, and historical sales information. Our main objective was to identify patterns that contribute to a game's success, enabling us to pinpoint games with high potential and strategize effective advertising campaigns.

The dataset we worked with pertains to the year 2016, and we are assuming a scenario where it is now December 2016, and we are tasked with planning a campaign for the upcoming year, 2017.

It's important to note that this dataset contains abbreviations, including ESRB, which stands for the Entertainment Software Rating Board. The ESRB is an independent regulatory organization responsible for evaluating game content and assigning age ratings such as Teen or Mature.

The objectives of this project are as follows:

1. Perform an analysis to identify patterns that contribute to the success or failure of a game.
2. Provide recommendations for games that show potential for advertising to enhance sales in 2017.
3. Test two hypotheses:
    - Determine if the average user ratings for Xbox One and PC platforms are equal.
    - Determine if the average user ratings for the Action and Sports genres are different.

## Data Description

We will analyze the data stored in the `games.csv` file. Although we have some preliminary information about the data, we need to assess its quality.

Here is a description of the data used for our analysis:

- `Name`: The name of the game.
- `Platform`: The platform(s) on which the game is available.
- `Year_of_Release`: The year the game was released.
- `Genre`: The genre or category of the game.
- `NA_sales`: Sales of the game in North America, measured in million USD.
- `EU_sales`: Sales of the game in Europe, measured in million USD.
- `JP_sales`: Sales of the game in Japan, measured in million USD.
- `Other_sales`: Sales of the game in other countries, measured in million USD.
- `Critic_Score`: The review score given by critics, with a maximum score of 100.
- `User_Score`: The review score given by users, with a maximum score of 10.
- `Rating`: The rating assigned by the Entertainment Software Rating Board (ESRB).

These variables provide important information about the games, including their sales performance, critical and user reviews, and ESRB ratings.

Here is the meaning of each rating based on the ESRB website:

- **E** (Everyone): Content suitable for all ages.
- **T** (Teen): Content suitable for teens aged 13 and above.
- **M** (Mature): Content suitable for adults aged 17 and above.
- **E10+** (Everyone 10 and older): Content suitable for everyone over 10 years old.
- **K-A** (Kids to Adults): Content suitable for all ages. This was the rating used before it was changed to E in 1999.
- **AO** (Adults Only): Content only suitable for adults aged 18 and above.
- **EC** (Early Childhood): Content suitable for children aged 3 and above.
- **RP** (Rating Pending): Ratings have not been issued by the ESRB yet.

## Hypothesis

We were assigned to test two hypotheses in this analysis, namely:
— The average user rating for the Xbox One and PC platforms is the same.
— The average user ratings for the Action and Sports genres are different.

## Stages

Our analysis will be conducted through several stages:

1. Initial Data Description: We will provide a brief overview of the dataset, including general information and key statistical measures.
2. Data Preprocessing: We will enhance the data quality by performing tasks such as data reading and validation, column renaming, handling missing values, adjusting data types, and creating new relevant columns.
3. Exploratory Data Analysis: We will explore the dataset to uncover patterns and insights related to video game sales performance. Our findings, insights, and recommendations will be presented based on this analysis.
4. Statistical Data Analysis: We will perform statistical tests to examine two specific hypotheses that have been formulated and accepted.
5. Conclusion: We will summarize the results of our analysis and provide overall conclusions based on the insights gained throughout the project.

By following these stages, we aim to conduct a comprehensive analysis of the dataset, enabling us to obtain valuable insights into video game sales.


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- SciPy version: 1.10.1
