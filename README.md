# Boom's Bike Sharing Project

## Problem Statement
The goal of this project is to analyze and predict the demand for shared bikes post-quarantine, considering various factors influencing bike rentals. The dataset includes daily bike demand across the American market based on meteorological surveys and user behaviors.

## Project Overview
- **Context:** BoomBikes, a US bike-sharing provider, aims to understand the demand for shared bikes post-lockdown to prepare for market resurgence.
- **Objective:** Predict bike demand based on factors such as year, season, temperature, weekdays, and more.
  
## Dataset Description
The dataset includes the following fields:
- `instant`, `dteday`, `season`, `yr`, `mnth`, `holiday`, `weekday`, `workingday`, `weathersit`, `temp`, `atemp`, `hum`, `windspeed`, `casual`, `registered`, `cnt`

## Steps Undertaken
### Step 1: Data Understanding and Preprocessing
- Handled missing values, outliers, and performed Exploratory Data Analysis (EDA).
- Visualized relationships between variables and bike demand.

### Step 2: Train-Test Split and Model Building
- Split data into train and test sets.
- Scaled features, built a multiple linear regression model, and performed feature selection based on VIF and p-values.

### Step 3: Residual Analysis
- Analyzed model residuals to validate assumptions and check for patterns in errors.

### Step 4: Predictions and Evaluation
- Made predictions using the model on the test dataset.
- Evaluated the model's performance using R-squared values for train and test sets.

## Assumptions of Linear Regression
Linear regression relies on several assumptions to be valid. Here are the assumptions considered during this analysis:

1. **Linearity:** Assumes a linear relationship between the dependent and independent variables.
2. **Independence:** Assumes that the residuals/errors of the model are independent.
3. **Homoscedasticity:** Assumes that the variance of errors is constant across all levels of the independent variables.
4. **Normality of Residuals:** Assumes that the residuals are normally distributed.
5. **No Multicollinearity:** Assumes no excessive correlation among independent variables (features).

These assumptions are essential to validate the model's reliability and interpretability.


## Conclusion
- Identified feature variables significantly influencing bike demand.
- The R Squred Value Is:0.806
- The Adj R Squred Value Is:0.801

## Technologies Used
- Pandas - version: 1.5.3
- Seaborn - version: 0.12.2
- Matplotlib - version 3.7.1
- Ploty - version 5.9.0

### Contributors
- **Zeba Firdows**
