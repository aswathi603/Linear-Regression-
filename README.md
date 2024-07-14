# Linear-Regression-
Machine Learning  In Python


Linear regression is a foundational statistical technique used to understand the relationship between a dependent variable (often denoted as Y) and one or more independent variables (often denoted as X). Its simplicity and interpretability make it a widely used method for predictive modeling and understanding data relationships.

Key Concepts:
Regression Line: In simple linear regression, the relationship between the independent variable X and the dependent variable 
Y is modeled as a straight line:
𝑌 = 𝛽 0 + 𝛽 1 ⋅ 𝑋 + 𝜖
where β 0 is the intercept (the value of Y when X is zero), β 1 is the slope (change in 𝑌 for a unit change in 𝑋), and 𝜖 is the error term representing the deviations of actual observations from the predicted line.


Objective: The goal of linear regression is to find the best-fit line that minimizes the sum of squared differences between the observed 𝑌 values and the values predicted by the model. This is typically achieved using the method of Ordinary Least Squares (OLS).

Assumptions: Linear regression assumes that:
There is a linear relationship between 𝑋 and 𝑌.
The errors (residuals) ϵ are normally distributed with a mean of zero.
The variance of the errors is constant (homoscedasticity).
The errors are independent of each other.


Interpretation: The coefficients 𝛽 0 and 𝛽 1 provide insights into the nature and strength of the relationship between X and Y. 
For example, a positive 𝛽 1 suggests that as  𝑋 increases, 𝑌 also tends to increase.

Applications: Linear regression is used in various fields such as economics, finance, social sciences, and more recently in machine learning for tasks such as predicting sales based on advertising spending, analyzing the impact of educational attainment on income, and forecasting housing prices based on location and other factors.

Conclusion:
Linear regression serves as a fundamental tool for understanding and quantifying relationships between variables. While it assumes a linear relationship between variables, it remains powerful due to its simplicity, interpretability, and wide applicability in both statistical analysis and predictive modeling contexts.


Linear Regression
Linear regression is a fundamental technique in statistics and machine learning for modeling the relationship between a dependent variable Y and one or more independent variables X.

1. Simple Linear Regression
Simple linear regression models the relationship between a single independent variable X and a dependent variable Y as a straight line:

𝑌 = 𝛽 0 + 𝛽 1 ⋅ 𝑋 + 𝜖

Objective: Predict Y based on X.

Key Concepts:
β 0: Intercept (value of Y when X is zero).
β 1: Slope (change in Y for a unit change in X).
ϵ: Error term (residuals).

Implementation Steps:
Data Collection: Gather paired data points of X and Y.
Model Training: Estimate β 0 and β 1 using Ordinary Least Squares (OLS).
Evaluation: Assess model performance using metrics like MSE, RMSE, and R 2.

2. Multiple Linear Regression
Multiple linear regression extends simple linear regression to include multiple independent variables:

Y=β 0 + β 1 ⋅ X 1 + β 2 ⋅ X 2 + … + β p ⋅ X p + ϵ

Objective: Predict Y based on 𝑋1,𝑋2,…,𝑋𝑝.

Key Concepts:
β 0 , β 1, … , β p : Coefficients for X 1,X 2,…,X p.
ϵ: Error term (residuals).

Implementation Steps:

Data Collection: Gather Y and multiple X variables.
Model Training: Estimate coefficients β 0,β 1,…,β p using OLS.
Evaluation: Evaluate model accuracy using metrics like MSE, RMSE, and R 2.


Usage
Applications: Linear regression is used in various fields such as economics, finance, and social sciences for predicting outcomes based on historical data and understanding relationships among variables.



