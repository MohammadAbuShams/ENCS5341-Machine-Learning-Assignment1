# Car Fuel Consumption Analysis

This project analyzes a dataset of cars with a focus on fuel consumption (mpg - miles per gallon). The analysis covers various aspects of data exploration, preprocessing, and machine learning to predict fuel efficiency using Python.

## Objectives

1. **Data Exploration**:
   - Load and explore the dataset (number of features and examples).
   - Identify missing values in the dataset.

2. **Data Preprocessing**:
   - Impute missing values using appropriate methods such as mean, median, or mode.

3. **Data Analysis**:
   - Compare fuel economy between different countries using visualizations (box plots).
   - Investigate the distribution of features like `acceleration`, `horsepower`, and `mpg` to determine their resemblance to a Gaussian distribution (histograms).

4. **Correlation Analysis**:
   - Analyze the relationship between `horsepower` and `mpg` using scatter plots and examine correlations.

5. **Machine Learning**:
   - Implement Simple Linear Regression (closed-form solution) to predict `mpg` based on `horsepower`.
   - Extend the model to a quadratic form (f = w0 + w1x + w2x²).
   - Implement Gradient Descent to solve the linear regression problem.

## Dataset

The dataset (`cars.csv`) contains information about various car attributes, including:
- `mpg`: Miles per gallon (fuel consumption).
- `horsepower`: Horsepower of the car.
- `acceleration`: Time taken to reach a certain speed.
- `origin`: The country of origin.

This dataset is used to analyze fuel efficiency, perform regression analysis, and make predictions based on car attributes.


### Prerequisites

- Python 3.
- Jupyter Notebook.
- Libraries: Pandas, NumPy, Matplotlib, Seaborn.


