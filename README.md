# California Housing Regression

This repository contains Python code for predicting median house values in California communities using various regression techniques. The analysis includes data preprocessing, model training, evaluation, and comparison to find the best model for predicting housing prices.

## Data Description

The dataset used in this analysis is from the 1990 census and includes various features such as median income, house age, average rooms, average bedrooms, population, and more. The target variable is the median house value.

## Code Overview

The Python code provided here performs the following tasks:

1. Loading and preprocessing the California housing dataset.
2. Training a linear regression model and evaluating its performance on training and test sets.
3. Training a Lasso regression model and comparing its performance with the linear regression model.
4. Training a Ridge regression model and comparing its performance with the linear regression model.
5. Visualizing RMSE values and coefficients of different models.
6. Analyzing and comparing the coefficients, RMSE values, and predicted values of the models.


Imports necessary Python libraries and modules for data analysis, visualization, and machine learning, including `numpy`, `pandas`, `seaborn`, `matplotlib`, and various components from `sklearn` such as `train_test_split`, `StandardScaler`, and regression models like `LinearRegression`, `Lasso`, and `Ridge`.

### Technical Overview
1. **Data Analysis and Preprocessing:**
   - Data is loading into a dataset using `pandas`, followed by exploratory data analysis (EDA) with `seaborn` and `matplotlib` for visualization.
   - Data preprocessing steps include handling missing values, feature scaling with `StandardScaler`, and encoding categorical variables if present.

2. **Model Building and Evaluation:**
   - The project uses `train_test_split` to divide the dataset into training and testing sets to evaluate the performance of the models.
   - It includes the implementation of linear regression models (`LinearRegression`, `Lasso`, `Ridge`) from `sklearn.linear_model`.
   - Model evaluation is performed using the mean squared error metric from `sklearn.metrics`, which assesses the models' performance in predicting the median house values.

3. **Regression Models:**
   - Linear Regression is used as a baseline model for predicting house values.
   - Lasso (L1 regularization) and Ridge (L2 regularization) regression models are applied to analyze their effectiveness in handling overfitting and to compare their performance against the baseline linear regression model.


