# Age Verification Model

## Project Description

Good Seed, a supermarket chain, has initiated a project to explore the application of Data Science in assisting them to comply with age-restriction laws. They seek to ensure that they are not selling age-restricted products to customers who are underage.

The company has equipped their stores with cameras in the cashier area, which can detect age-restricted products during transactions. In order to verify a person's age, they aim to employ computer vision techniques capable of determining an individual's age from a photograph.

We completed this project on Practicum's or TripleTen's platform, utilizing their GPU facilities to expedite the machine learning process. Below, we present the results obtained.

## Objective

The objective of this project is to build and evaluate a model that can accurately verify a person's age based on the photographs captured by the cameras in the cashier area. By doing so, Good Seed aims to ensure compliance with age-restriction regulations, prevent sales to underage customers, and uphold legal requirements.

Our task is to build and train a convolutional neural network on a GPU platform using a dataset containing human photographs. The objective is to achieve an MAE score of no greater than 8 for the test set.

## Data Description

The required datasets are stored in the `/datasets/faces/` folder on Practicum Platform and include the following:

- The `final_file` folder containing approximately 7.6k photos.
- The file `labels.csv`, which contains the corresponding labels for the images, with two columns: `file_name` and `real_age`.

Due to the large number of image files, it is advisable not to read them all simultaneously, as it may consume excessive computing resources. Instead, we recommend using the ImageDataGenerator to create a generator.

The file containing labels, `labels.csv`, can be easily loaded as a plain CSV file, providing convenient access to the associated image labels for further processing and analysis.

## Stages

This project will be completed through the following stages:

- Import computer vision libraries and load the available data.
- Conduct exploratory data analysis, including descriptive statistics, visualization of sample data, augmentation analysis, class distribution analysis, and image quality analysis.
- Proceed to the modeling phase, where functions will be created for execution on Practicum's GPU platform.
- Develop coding scripts based on the functions to be executed on the GPU platform.
- Record the output from the GPU platform in markdown cells.

## Libraries
- Pandas version: 1.4.4
- Matplotlib version: 3.7.1
- Seaborn version: 0.12.2
- TensorFlow version: 2.12.0

