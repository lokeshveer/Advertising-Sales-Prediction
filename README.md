# Advertising-Sales-Prediction
This project aims to predict sales based on advertising expenditures using Linear Regression and other regression techniques. The dataset includes advertising spending on TV, Radio, and Newspaper and their corresponding sales figures.
Dataset Details

Dataset Name: Advertising Sales Dataset

Features:

TV: Advertising budget for TV (independent variable)

Radio: Advertising budget for Radio (independent variable)

Newspaper: Advertising budget for Newspaper (independent variable)

Sales: Total sales generated (dependent variable)

Objective: Build a regression model to predict Sales based on advertising budgets.

Steps to Implement

1. Data Exploration

Load the dataset using pandas.

Display the first few rows using .head().

Check for missing values and data types with .info() and .describe().

2. Data Preprocessing

Handle missing values (if any).

Identify outliers using box plots.

Perform feature selection to determine significant variables.

Split the dataset into 80% training and 20% testing sets.

3. Model Implementation

Linear Regression

Train a Linear Regression model using TV, Radio, and Newspaper as input features.

Fit the model and generate predictions.

Alternative Models

Ridge Regression: Regularized linear regression to reduce overfitting.

Lasso Regression: Feature selection by shrinking less important coefficients to zero.

Polynomial Regression: Fits a polynomial equation for better accuracy if data shows non-linearity.

4. Model Evaluation

Predict sales values on the test set.

Evaluate performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Visualize predicted vs actual sales with scatter plots.

Installation & Usage

Clone the repository:

Navigate to the project directory:

Install dependencies:

Run the script:

Insights

TV and Radio advertising have a stronger impact on sales compared to Newspaper advertising.

Lasso Regression may eliminate features with less influence, such as Newspaper.

Polynomial Regression can improve accuracy if the relationship is non-linear.

Contributors

Lokesh Veeramalla

Contact: lokeshveeramalla7@gmail.com

License

This project is for educational purposes. You may modify and use it as needed.


