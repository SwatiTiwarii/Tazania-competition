The competiton works on data provided by Tanzanian Ministry of Water and we have to determine the condition of water pumps.
We have to create a classification model to predict whether a given handpump is defective or not. 

This competition provides challenge to work with small data with significant percentage of missing values. We need to perform exploratory data analysis, data pre processing involving steps such as capping/flooring, missing value imputation to create useful predictive features for our model. 
First notebook describes exploratory data analysis on raw data. The correlation and patterns of different features with respect to target feature is observed. Subsequent notebooks contain details on missing value imputations, feature engineering steps. Here we have tried different imputations techniques and finally keeping the technique providing better out of sample f1 score after creating the model.
For modelling purpose, we start out by trying Logistic Regression, then move to tree based approaches such as Random Forest and LightGBM. 

