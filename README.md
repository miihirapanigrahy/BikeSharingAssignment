# Bike Sharing Assignment

Linear Regression Assignment - Build a model for prediction of bike rental daily count based on the environmental and seasonal conditions

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

### Problem Statement
BoomBikes, a bike-sharing system, is a service in which bikes are made available to individuals for shared use. BoomBikes aspires to understand the factors on which the demand for these shared bikes depends. The company wants to know:
1. which variables are significant in predicting the demand for shared bikes.
2. how well those variables describe the bike demands

The business goal is to model the demand for shared bikes, understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.

### Dataset

1. day.csv
2. Data Dictionary

The dataset has 730 rows and 15 columns. No missing values, very clean data.

## Conclusions

### Conclusion 1
Univariate Analysis indicates on numerical variable "Windspeed" has outliers.
Univariate Analysis of categorical data indicates:
- Holiday
  - Majority of bike hires are on holidays
  - This information matches with "Working day" or "Not working day"
- Weather Situation: Less bike hires on snowy or rainy days
 
### Conclusion 2

Bivariate & Multicollinearity Analysis indicates:
- "Temp" and "atemp" are highly correlated
- Bike hires count is more on holidays compared to non-holidays
- Bike hires are uniform across all week days
- Weather situation impacts bike hires. Bad weather has less hires

### Conclusion 3

The Linear regression model indicates demand for bikes is highly dependent on variables such as year, temperature and weather situation.

## Technologies Used
1. Python, Stats Models, Jupyter Notebook
2. SciKit-Learn

## Acknowledgements


## Contact
Created by [Mihira Panigrahy]
