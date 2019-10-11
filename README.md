# Project_2
Notebook is separated into the following main parts:
1) Problem Statement
  - Predict house prices from features
  - Which features are the best predictors of house prices? 
2) Import Libraries
3) Data cleaning
  - Drop/recode missing data
4) EDA
  - Plot graphs for features against saleprice
5) Create Dataframe
  - Map Ordinal variables and create dummy variables for Nominal variables
  - 209 features
6) First Model
  - Lasso Regression fitted with 209 features
  - reduction of 209 to 25 features based on coefficients that cause the greatest increase in saleprice
7) Second Model
  - Ridge regression fitted with 25 features
8) Use Model on Test Data
  - Fit Test data to second model
  - Predict data with Second model
