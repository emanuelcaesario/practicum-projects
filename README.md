# Movie Sentiment Analysis

[Project Presentation](https://www.canva.com/design/DAFs_hDrYwo/GbHNTDFUMbnkzu2ltB3ZOQ/view?utm_content=DAFs_hDrYwo&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink#1)

[Project Notebook](https://github.com/emanuelcaesario/practicum-projects/blob/Project-14-Machine-Learning-for-Text/Project%2014%20Machine%20Learning%20for%20Text.ipynb)

## Project Description

Film Junky Union, a new community for classic film fans, is currently developing a system to filter and categorize movie reviews. The objective is to train a model capable of automatically detecting negative reviews. Our task is to utilize the IMBD film review dataset with polarity labeling and create a model that can accurately classify positive and negative reviews. The set goal for this model is to achieve an F1 score of at least 0.85.

## Data Description

The data is stored in the file `imdb_reviews.tsv`.

This dataset was obtained from Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011).

Here are the descriptions for the selected columns:
- `review` — review text
- `pos` — target, '0' for negative and '1' for positive
- `ds_part` — 'train'/'test' for the train/test part of the dataset

These three columns are the main focus of our attention in this task. However, it is worth noting that there are also other columns present in the dataset.

## Stages

This project will be completed through the following stages:

1. Loading and studying the data.
2. Performing initial data pre-processing.
3. Conducting exploratory data analysis (EDA) and addressing class imbalances.
4. Performing data pre-processing to prepare the data for modeling.
5. Training at least three models using the existing training dataset.
6. Evaluating the models on the existing test dataset.
7. Writing additional reviews and classifying them using all models.
8. Analyzing and comparing the model test results from the two points above, and providing an explanation for the observed differences.

## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- NLTK version: 3.7
- Regex version: 2.2.1
- spaCy version: 3.3.1
- Scikit-learn version: 1.2.2
- CatBoost version: 1.1.1
- LightGBM version: 3.3.5
- XGBoost version: 1.7.3

