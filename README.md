# Tazania-competition
Providing solution notebooks for Tazania Competition: https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/

The data is subset of original Tazania Competition and the classification is for 2 classes only. The task is to create a 
classification model to predict whether a given handpump is defective or not. 

First notebook describes exploratory data analysis on raw data. The correlation and patterns of different features with respect to target feature is observed. 
Subsequent notebooks contain details on missing value imputations, feature engineering and iterations of Random Forest and LightGBM classifier.

Because of present of various categorical features, LightGBM is out performing RandomForest. Next we want to try out CatBoost on this data set.
