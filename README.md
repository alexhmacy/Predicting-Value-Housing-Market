
# Module 2 Final Project


## Introduction

Import, explore, clean, standardize, and model the King County House Sales dataset with a multivariate linear regression to predict the sale price of houses as accurately as possible.

We want to know the underlying influencers on sale price, and how they can be adjusted in order to increase or decrease the final measured quantity. Such metrics would include p-values associated with the various features, comparing models, and investigating potential multicollinarity in the model. Multicollinearity also touches upon checking model assumptions.

## Exploratory Data Analysis
1. Import the Dataset
2. Explore the Dataset
3. Visualize the Dataset with a Heat Map

## Hypotheses
Alternative Hypothesis:
There is a multivariate relationship between the price of a house and its total square feet, the number of bedrooms, bathrooms, year built and renovated, zipcode, and the lat and longitude.

Null Hypothesis:
There is no relationship between these variables.

## Methodology and Approach 
This will be a supervised learning task with a plain batch. Instances are labeled with predictor values corresponding to a target variable. Furthermore, this will be a regression analysis where I will predict values. And since this dataset has multiple predictor values for a single target variable, this will be a multivariate regression.

## Performance Measure
For this regression analysis, I will be using the Root Mean Squre Error to get an idea of how much error my model makes in its predictions prices.

## To answer the Questions:
Question 1: What are my assumptions? Is my data decribed by these assumptions?
Question 1a. Is my data normally distributed?
Question 1b. Is my data linearly related?
Question 1c. Is my data homoscedastic?
Question 2: Which attributes have the highest correlation?
Question 3: Are my training and test sets represenative?
Question 4: Does my Linear Regression accurately predice prices?
Question 5: What is the measure of error in my model?

## Followed by:
1. Data Cleaning-- droping Nan/Null values, imputing with median values, and removing outliers.
2. Feature Normalization-- with Min-Max Scaling and Log Transformations
3. Stratified Sampling-- to ensure my traning and test sets are representative of my dataset as a whole.
4. Linear Regression
5. RMSE-- to calculate the errors in my model
6. Plotting errors-- the guage homoscedasticity
