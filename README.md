# Resampling Methods in Polynomial and Poisson Regression

This project explores the use of various resampling methods such as cross-validation, the validation set approach, and Bootstrap to evaluate the predictive performance of polynomial and Poisson regression models. The dataset used pertains to predicting mortality rates and bird counts based on specific predictors.

# Project Overview

The goal of this project is to investigate different resampling techniques to assess the predictive power of polynomial and Poisson regression models. Specifically, we evaluate models of varying polynomial degrees using cross-validation and bootstrap to estimate standard errors of model parameters.

# Dataset
The project involves two datasets:

1. Mortality and July Temperature Dataset:
* JULT: Average July temperature in degrees F.
* MORT: Total age-adjusted mortality rate per 100,000.

2. Bird Count Dataset:
* Year: Year of bird count.
* Count: Bird count for a given year.

# Libraries Used
* Pandas: For data manipulation.
* NumPy: For numerical computations.
* Matplotlib: For visualization.
* Scikit-learn: For regression models and cross-validation.
* SciPy: For optimization.

# Resampling Methods
1. Validation Set Approach
* Data is split into training and testing sets (50/50 split).
* Polynomial models of degree 1 to 4 are evaluated, and the Mean Squared Error (MSE) is calculated for both sets.
  
2. Cross-Validation
* K-fold cross-validation is applied to evaluate the model's performance for degree 2.
  
3. Bootstrap
* Bootstrap resampling is used to estimate the standard error of the slope parameter ($\beta_1$) ​in a Poisson regression model.





