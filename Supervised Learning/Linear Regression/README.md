# Linear Regreesion

## Introduction

In statistics, linear regression is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables (also known as dependent and independent variables). The case of one explanatory variable is called simple linear regression; for more than one, the process is called multiple linear regression.

Linear regression has many practical uses. Most applications fall into one of the following two broad categories:

If the goal is prediction, forecasting, or error reduction, linear regression can be used to fit a predictive model to an observed data set of values of the response and explanatory variables. After developing such a model, if additional values of the explanatory variables are collected without an accompanying response value, the fitted model can be used to make a prediction of the response.
If the goal is to explain variation in the response variable that can be attributed to variation in the explanatory variables, linear regression analysis can be applied to quantify the strength of the relationship between the response and the explanatory variables, and in particular to determine whether some explanatory variables may have no linear relationship with the response at all, or to identify which subsets of explanatory variables may contain redundant information about the response.

## File

"Linear Regression.ipynb" contains the description and code of Linear Regression algorithm, then it's applied on *diabetes* dataset loaded from *sklearn.datasets*.


## Dataset

"Diabetes dataset" is a classic regression dataset. The total sample size is 442; 10 Dimensionality.
Features:
Ten baseline variables: age, sex, bmi(body mass index), bp(average blood pressure), and six blood serum measurements:
s1 tc, total serum cholesterol
s2 ldl, low-density lipoproteins
s3 hdl, high-density lipoproteins
s4 tch, total cholesterol / HDL
s5 ltg, possibly log of serum triglycerides level
s6 glu, blood sugar level
Column 11 is a quantitative measure of disease progression one year after baseline

Each of these 10 feature variables have been mean centered and scaled by the standard deviation times n_samples (i.e. the sum of squares of each column totals 1).

## Reference

Sklearn.datasets.load_diabetes. scikit. (n.d.). Retrieved May 6, 2022, from https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html#sklearn.datasets.load_diabetes 

Wikimedia Foundation. (2022, April 21). Linear regression. Wikipedia. Retrieved May 6, 2022, from https://en.wikipedia.org/wiki/Linear_regression 