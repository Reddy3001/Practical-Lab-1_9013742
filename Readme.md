# Practical Lab 1: Univariate Linear Regression on California Housing Prices

## Project Overview

This project involves performing univariate linear regression analysis to estimate median house values in California based on three independent variables:

- Median income
- Population
- Number of households

The objective is to evaluate and compare the predictive power of each feature using standard regression metrics. This lab is part of the coursework for [Course Name / Code] at [Institution Name].


## Machine Learning Workflow

The analysis is structured according to the standard machine learning process:

1. **Problem Definition** – Clarify the objective of the regression analysis.
2. **Data Import** – Load and inspect the dataset using Pandas.
3. **Exploratory Data Analysis** – Use descriptive statistics and scatter plots to understand the relationships.
4. **Model Development** – Fit separate linear regression models for each independent variable using Scikit-learn.
5. **Model Evaluation** – Evaluate each model using Mean Squared Error (MSE) and Mean Absolute Error (MAE).
6. **Visualization** – Plot regression lines and overlay error metrics.
7. **Conclusion** – Summarize findings and recommend the best predictor variable.

## Dataset Information

**Source**: [California Housing Prices Dataset - Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

This dataset includes housing and demographic data at the block level across various districts in California. It contains information such as income, population, household count, and housing prices.

## Summary of Results

- The model using **median income** as the predictor produced the lowest error rates and demonstrated a strong linear relationship.
- **Population** had the weakest correlation with housing prices and the highest error.
- **Number of households** showed a moderate correlation, performing better than population but not as well as income.

Based on these results, **median income** is recommended as the most effective single predictor for estimating median house values.
