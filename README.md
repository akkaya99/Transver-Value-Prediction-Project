# Transver-Value-Prediction-Project
In this project, it is aimed to determine which of the various machine learning algorithms works with higher accuracy by using the football player transfers between the years 2000-2018. The dataset is taken from Kaggle. The following steps were applied in the project, respectively.

1.) The libraries to be used in the project have been imported.
2.) The data set has been read.
3.) The first 10 and last 10 rows of the data set were examined.
4.) The data types of the variables in the data set were examined.
5.) The number of missing data in the data set was checked.
6.) The statistical values of the numerical variables in the data set were examined.
7.) The values of the numerical variables in the data set were shown on the graph.
8.) Outlier detection done. Although the value of 35 appeared as an outlier in the age variable, this value was not changed since transfer is possible at this age. But the value of 0 was replaced with the mean of this category. Since the data may be correct in the transfer fee and market value variables, no changes were made.
9.) The numbers of missing data have shown on the graph.
10.) Missing values in the Market value variable have been updated as the average of this category.
11.) Position and season variables have been made categorical.
12.) Variables that do not contain numeric values were excluded from the data set, as it was intended to work only with numeric values.
13.) Dependent and independent variables were determined.
14.) The data set was divided into two as test and train.
15.) KNN, CART, Random Forest, XGB, Light GBM and CatBoost algorithms were modeled on the data set. RMSE values found.
16.) Tuning was done after each model.

Conclusion: CatBoost algorithm gave the best results on this data set.
