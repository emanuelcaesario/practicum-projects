# Gold Extraction Model

[Project Presentation](https://www.canva.com/design/DAFqo2anKa8/TInO1VSwLwCaO8qEF7YSCg/view?utm_content=DAFqo2anKa8&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink#30)

## Project Overview

We were tasked with developing a prototype machine learning model for Zyfra, a company specializing in efficient solutions for the heavy industry sector.

The objective was to design a model capable of predicting the amount of gold extracted from gold ore, using data related to the extraction and refining process.

The purpose of this model is to optimize the production process and eliminate non-profitable parameters.

To accomplish this project, we were instructed to:
- Prepare the available data
- Perform data analysis
- Develop and train the models


## Data Description

The data we get is stored in three files, namely:
- `gold_recovery_train.csv`
- `gold_recovery_test.csv`
- `gold_recovery_full.csv`

**Technological Process**
- `Rougher feed` — Raw material used in the flotation process.
- `Rougher additions` (or reagent additions) — Reagents added during flotation: Xanthate, Sulphate, Depressant.
- `Xanthate` — Flotation activator.
- `Sulphate` — Sodium sulfide used specifically for this process.
- `Depressant` — Sodium silicate used as a depressant.
- `Rougher process` — Flotation process.
- `Rougher tails` — Residue or by-product from the flotation process.
- `Float banks` — Flotation units or cells.
- `Cleaner process` — Purification process.
- `Rougher Au` — Coarser gold concentrate obtained from the flotation process.
- `Final Au` — Final gold concentrate after purification.

**Parameters of Existing Stages**
- `air amount` — air volume
- `fluid levels`
- `feed size` — feed particle size
- `feed rate`

**Feature Naming**

To name the existing features, follow the format: 
`[stage].[parameter_type].[parameter_name]`
For example: `rougher.input.feed_ag`

Possible values for `[stage]`:
- *rougher* — flotation stage
- *primary_cleaner* — first purification stage
- *secondary_cleaner* — second purification stage
- *final* — final stage

Possible values for `[parameter_type]`:
- *input* — raw material parameters
- *output* — product parameters
- *state* — parameters indicating the current stage characteristics
- *calculation* — calculated characteristics
 

## Project Instructions

**1. Data Preparation**

- Open the files and examine the data.
    - Filepaths:
        - `gold_recovery_train.csv`
        - `gold_recovery_test.csv`
        - `gold_recovery_full.csv`
- Verify the correctness of the gold recovery calculation. Calculate the recovery rate for the `rougher.output.recovery` feature using the training set. Calculate the mean absolute error (MAE) between your calculation and the actual feature values. Please provide the results of your calculation.
- Analyze the features that are not available in the test set. What are these parameters? What types of parameters are they?
- Perform data preprocessing.

**2. Data Analysis**

- Take note of how the concentration of metals (Au, Ag, Pb) changes at different stages of purification.
- Compare the particle size distribution of the feed in the training set and the test set. If there is a significant variation in the distribution, it could lead to erroneous evaluation of the model.
- Examine the total concentrations of all substances at different stages: raw feed, coarser concentrations, and final concentrations. Look for any abnormal values in the distribution of the totals. If you find any anomalies, determine if it is necessary to remove those values from both the training and test sets. Describe your findings and provide a rationale for handling the anomaly.

**3. Model Creation**

- Define a function to calculate the final sMAPE (symmetric mean absolute percentage error) value.
- Train different models and evaluate their performance using cross-validation. Select the best model and test it using a separate test dataset. Share your findings and results.
- Utilize the following formula for evaluating the performance metrics:

![image](https://github.com/emanuelcaesario/practicum-project/assets/118190295/a0788aab-77ef-45c1-a91d-bf7bd68c5a30)

where:
- `N` is the number of samples
- `yi` is the true target values
- `ŷi` is the predicted target values


## Libraries
- Pandas version: 1.4.4
- NumPy version: 1.23.5
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- Scikit-learn version: 1.2.2
