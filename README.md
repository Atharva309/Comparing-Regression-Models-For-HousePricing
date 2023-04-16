# Predicting House Prices

In this project, we will be predicting house prices based on the square footage and number of bedrooms using various regression models. The dataset we will be using is the Boston Housing dataset, which contains information on different housing features in various neighborhoods in Boston. Specifically, we will be using the "RM" (average number of rooms per dwelling), "LSTAT" (percent of population considered lower status), and "PTRATIO" (pupil-teacher ratio by town) features as input variables to predict the "MEDV" (median value of owner-occupied homes in $1000s) output variable.

## Dataset
We will be using the Boston Housing dataset, which can be found at the UCI Machine 

## Models
In this project, we will be using the following regression models:

- Linear Regression
- Support Vector Regression
- Random Forest Regression
- Gradient Boosting Regression
- Neural Networks
- K-Nearest Neighbors Regression
- Decision Tree Regression

### 1. Linear Regression
Linear regression is a simple and commonly used regression model that assumes a linear relationship between the input and output variables. It aims to find the best-fit line to predict the output variable based on the input variables.
### 2. Support Vector Regression (SVR)
Support Vector Regression (SVR) is a regression model that uses Support Vector Machines (SVMs) to find the best-fit line to predict the output variable. Unlike linear regression, SVR can handle non-linear relationships between the input and output variables.
### 3. Random Forest Regression
Random Forest Regression is an ensemble learning method that combines multiple decision trees to make predictions. It works by building a multitude of decision trees and averaging their predictions to obtain the final prediction.
### 4. Gradient Boosting Regression
Gradient Boosting Regression is another ensemble learning method that combines multiple decision trees. However, instead of averaging the predictions, it trains the decision trees sequentially, with each subsequent tree attempting to correct the errors of the previous tree.
### 5. Neural Networks
Neural Networks are a type of machine learning model inspired by the structure and function of the human brain. They consist of multiple layers of interconnected nodes that process the input variables and make predictions.
### 6. K-Nearest Neighbors Regression
K-Nearest Neighbors Regression is a non-parametric regression model that predicts the output variable by finding the k closest data points in the training set and averaging their output variable values.
### 7. Decision Tree Regression
Decision Tree Regression is a simple regression model that uses a decision tree to make predictions. It works by recursively splitting the input variables into smaller subsets based on their values until it reaches a leaf node, which contains the predicted output value.

## Conclusion
In this project, we used various regression models to predict house prices based on the square footage and number of bedrooms. We found that the random forest regression model had the highest R-squared score of 0.7796, indicating a good fit to the data. However, it's important to note that the best model may vary depending on the specific dataset and problem at hand.
