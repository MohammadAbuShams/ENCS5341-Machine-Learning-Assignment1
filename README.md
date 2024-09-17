# Car Fuel Consumption Analysis

This repository contains a Python-based analysis of a car dataset, focusing on fuel consumption and the relationships between various car features. The analysis includes data preparation, feature imputation, and model implementation using linear and quadratic regression, as well as gradient descent.

## Objectives

1. **Data Preparation**
   - Load and examine the dataset.
   - Identify features with missing values and handle them appropriately.
   - Visualize the dataset using histograms and box plots.

2. **Polynomial and Ridge Regression**
   - Implement polynomial regression with degrees ranging from 1 to 10.
   - Apply ridge regression and find the optimal regularization parameter.

3. **Logistic Regression**
   - Implement logistic regression with linear and quadratic decision boundaries.
   - Compare model performances in terms of accuracy.

## Dataset

- `cars.csv`: Contains data on car features including fuel consumption, horsepower, and more.

## Implementation

### Part 1: Dataset Examination

- Read the dataset using Pandas and determine the number of features and examples.

### Part 2: Missing Values

- Identify features with missing values and count them.

### Part 3: Imputation

- Fill missing values using mean for numerical features and mode for categorical features.

### Part 4: Fuel Economy Analysis

- Use a box plot to compare fuel economy (MPG) across different countries of manufacture.

### Part 5: Feature Distribution

- Analyze the distribution of features ('acceleration', 'horsepower', 'mpg') using histograms and determine which feature most closely resembles a Gaussian distribution.

### Part 6: Quantitative Measure

- Use skewness and kurtosis to quantitatively assess the Gaussian-like distribution of features.

### Part 7: Scatter Plot Analysis

- Plot 'horsepower' against 'mpg' to observe the correlation between them.

### Part 8: Linear Regression

- Implement the closed-form solution of linear regression to predict 'mpg' from 'horsepower' and plot the regression line.

### Part 9: Quadratic Regression

- Extend the linear regression model to a quadratic function and visualize the quadratic regression curve.

### Part 10: Gradient Descent

- Implement gradient descent to learn a linear model for predicting 'mpg' from 'horsepower' and plot the results.

## Prerequisites

- Python 3
- Jupyter Notebook
- Required Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `scipy`
