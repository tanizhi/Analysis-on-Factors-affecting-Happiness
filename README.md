# World Happiness Report

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence)

There are multiple factors including GDP per capita, Life expectancy, Social support, etc. that influence the happiness levels and scores in countries around the world.
We are conducting a data exploratory analysis on the Happiness Score Levels around the world, and determining what factors influence them the most. For a detailed explanation of our project, please view the source codes in the following orders:
1. Data Extraction and Cleaning
2. Data Cleaning - Filiing in NULL values
3. Exploratory Data Analysis
4. Linear Regression
5. Gradient Boosting
  
## Contributors

- Tan Izhi
- Ng Xing Yi Amanda
- Lee Pei Xuan Rachel

## Problem Definition

- Which variable would be the most important in influencing the Happiness Score Levels in different countries?
- Which model would be the best to predict it?

## Models Used

1. Linear Regression
2. Gradient Boosting

## Conclusion
- GDP per Capita is the most important factor in affecting the happiness scores in countries.
- However, for countries to most effectively improve their happiness scores, they need to improve their performances in multiple variables concurrently as a multivariate model has a stronger correlation to happiness scores than all univariate models. 
- Gradient boosting is a more accurate machine learning model than linear regression in determining the correlations between variables for this dataset.

## What did we learn from this project?
- We leant how to implement Multiple Imputation by Chained Equation (MICE) to fill in the NULL values within the variable using mean values before performing linear regression to obtain more accurate results prediction for our data points.
- We learnt that combining multiple factors for a multivariate linear regression produces a stronger correlation compared to a univariate linear regression model. 
- We also learnt how to implement gradient boosting as a machine learning model to determine the correlations between variables in our dataset.

## Presentation Slides
https://docs.google.com/presentation/d/1unfEYtUzT9zedxNKUUy26GXr6_KEPd7Jz8DtJlUayss/edit#slide=id.p

## References
- https://www.kaggle.com/datasets/yamaerenay/world-happiness-report-preprocessed?select=2020_report.csv
- https://scikit-learn.org/stable/modules/impute.html
- https://www.datacamp.com/tutorial/techniques-to-handle-missing-data-values
- https://machinelearningmastery.com/gradient-boosting-machine-ensemble-in-python/
