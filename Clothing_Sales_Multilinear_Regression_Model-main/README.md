# Clothing_Sales_Multilinear_Regression_Model

This repository contains Python code for a multilinear regression analysis used to predict total sales (`tsales`) of a product or item based on several independent variables. The analysis includes data preprocessing, model training, and model evaluation.

## Overview

In this analysis, we utilize Python libraries such as pandas, statsmodels, numpy, and seaborn to perform multilinear regression on a dataset containing information about products. The primary steps of the analysis include:

1. **Data Loading:** We load the dataset from a CSV file (`"Clothing.csv"`), and we select specific variables of interest for the analysis.

2. **Data Analysis:** We calculate summary statistics for the selected variables and create a correlation matrix heatmap to visualize the relationships between these variables.

3. **Multilinear Regression Preparation:** We prepare the dependent variable (`tsales`) and independent variables of interest (`margin`, `nown`, `inv1`, `inv2`, `ssize`, `start`) for modeling. We also split the data into training and test sets.

4. **Multilinear Regression Modeling:** We build a multilinear regression model using the `statsmodels` library. The model aims to predict total sales (`tsales`) based on the selected independent variables.

5. **Model Evaluation:** We assess the model's accuracy using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Requirements

To run the code in this analysis, you'll need:

- Python (>=3.6)
- Jupyter Notebook (for running the code interactively)
- Necessary Python libraries (pandas, statsmodels, numpy, seaborn, scikit-learn)
