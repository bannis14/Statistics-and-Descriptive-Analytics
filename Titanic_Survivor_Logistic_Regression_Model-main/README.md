# Titanic_Survivor_Logistic_Regression_Model

This repository contains Python code for a logistic regression analysis of the Titanic dataset to predict passenger survival. The analysis includes data preprocessing, exploratory data analysis (EDA), logistic regression modeling, and model evaluation.

## Overview

In this analysis, we utilize various Python libraries, including pandas, numpy, seaborn, and statsmodels, to perform logistic regression on the Titanic dataset. The primary steps of the analysis include:

1. **Data Loading:** We load the Titanic dataset from a CSV file, drop unnecessary columns (e.g., 'Name'), and create dummy variables for categorical features.

2. **Exploratory Data Analysis (EDA):** EDA includes generating histograms to visualize the distribution of key features, removing outliers to improve model performance, and creating a correlation matrix to understand feature relationships.

3. **Data Splitting:** We split the dataset into training and testing sets using the `train_test_split` function from `sklearn`.

4. **Logistic Regression Modeling:** We build a logistic regression model using the `statsmodels` library. The model aims to predict passenger survival (1 for survived, 0 for not survived) based on various features.

5. **Model Evaluation:** We assess the model's performance using metrics such as accuracy, the F1 score, specificity, sensitivity, and generate a classification report.

## Requirements

To run the code in this analysis, you'll need:

- Python (>=3.6)
- Jupyter Notebook (for running the code interactively)
- Necessary Python libraries (pandas, numpy, seaborn, statsmodels, scikit-learn)

