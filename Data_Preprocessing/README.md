# ML_DataPreprocessing

This repository contains notebook file which includes data preprocessing steps using for Machine Learning.

The main objective of this project is to design and implement a robust data
preprocessing system that addresses common challenges such as missing values, outliers,
inconsistent formatting, and noise.

By performing effective data preprocessing, the project aims to enhance the quality, reliability,
and usefulness of the data for machine learning.

DataSet: Employee.csv

Steps Involved:
1. Data Exploration:
    - Exploring the data, list downs the unique values in each feature and finds its length.
    - Performs the statistical analysis and renaming of the columns.
2. Data Cleaning:
    - Finds the missing and inappropriate values and treats them appropriately.
    - Removes all duplicate rows.
    - Finding the outliers.
    - Replacing the value 0 in age as NaN. Then treats the null values in all columns using any measures(removing/ replace the values with mean/median/mode).
3. Data Analysis:
    - Filters the data with age > 40 and salary < 5000 and plot the chart with age and salary.
    - Counts the number of people from each place and represent it visually
4. Data Encoding:
    - Converts categorical variables into numerical representations using techniques such as one-hot encoding, label encoding, making them suitable for analysis by machine learning algorithms.
5. Feature Scaling:
    - After the process of encoding, perform the scaling of the features using standardscaler and minmaxscaler.