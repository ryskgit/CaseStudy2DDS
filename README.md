# DDS-Case-Study-2

Author: Richard Kim

Date: 12/08/2021

Purpose:
The purpose of this project is to create a model that can accurately predict attrition in a company. The specific task was to explore a multitude of variables and identify the best predictors for attrition.

Conclusion:
We first developed a regression model to predict monthly income, which was used to impute missing data. A total of 3 variables were used to create a model with 95% adjusted R squared and 1161 RMSE.

We then used the imputed income data along with a number of other variables to develop a Naive-Bayes classification model for attrition. The model was able to identify whether an employee had left at 66.39% accuracy, 65% sensitivity, and 73% specificity, where the positive class was 'no attrition'. 
