java c
ISE529 Predictive Analytics 
2024 Fall 
Homework 2 
Due by: Oct. 1, 2024, 11:59 PM
1. (20 points)
Consider the following computer output.

(a) Fill in the missing quantities.
(b) What conclusions can you draw about the significance of regression?
(c) What conclusions can you draw about the contributions of the individual regressors to the model?
Note: check the critical value in the F-distribution ort-distribution table.
2. (20 points)
A study was performed on wear of a bearing and its relationship to x1 = oil viscosity and x2 = load. The data can be found in attached file bearingdata.csv.
(a) Fit a multiple linear regression model in the form. of y = β0  + β1x1 + β2 x2  + ε . Write out the estimated model.
(b) Estimate σ2 and compute the t-statistics for each regression coefficient. Using α = 0.05, what conclusions can you draw?
(c) Test for significance of overall regression using α = 0.05. What is the P-value for this test? What are your conclusions?
(d) Use the model to predict wear when x1 = 25 and x2 = 1000.
(e) Use the extra sum of squares method to investigate the usefulness of adding x2 = load to a model that already contains x1 = oil viscosity. Use α = 0.05.
(f) Refit the model with an interaction term. Test for significance of regression using α = 0.05.
(g) Use the extra sum of squares method to determine whether the interaction term contributes significantly to the model. Use α = 0.05.
3. (20 points)
We have used a sample of 30 observations to fit a regression model. The full model has 9 regressors, the variance estimate is σ^ 2   = MSE   = 100, and R2  = 0.92.
(a) Calculate the F-statistic for testing significance of regression. Using α = 0.05, what would you conclude?
(b) Suppose that we fit another model using only four of the original regressors and that the   error sum of squares for this ne代 写ISE529 Predictive Analytics 2024 Fall Homework 2Python
代做程序编程语言w model is 2200. Find the estimate of σ2 for this new reduced model. Would you conclude that the reduced model is superior to the old one? Why?
(c) Find the value of Cp for the reduced model in part (b). Would you conclude that the reduced model is better than the old model?
4. (20 points)
Use the Carseats data set (attached Carseats.csv) to answer the following questions. (a) Fit a multiple regression model to predict Sales using Price, Urban, and US.  (b) Provide an interpretation of each coefficient in the model.
(c) Write out the model in equation form, show the qualitative variables properly.
(d) For which of the predictors can you reject the null hypothesis H0: βj = 0?(e) On the basis of your response to the previous question, fit a smaller model that only uses  the predictors which is statistically significant. Compare it to the model in (a), which one is a better model?
(f) Using the model from (e), obtain 95 % confidence intervals for the coefficient(s).
5. (20 points)
Perform. the following Python code to generate simulated data, and answer the following questions:

(a) Write out the form. of the underlying true linear model. What are the regression coefficients?
(b) Use function corr() to calculate the correlation between x1 and x2 ? Create a scatterplot matrix displaying the relationship between the variables.
(c) Using this data, fit a linear regression model to predict y using x1 and x2. Describe the
results obtained. Can you reject the null hypothesis H0: β1 = 0 and/or null hypothesis H0: β2 = 0?
(d) Now fit a least squares regression to predict y using only x1 or using only x2 respectively.   Comment on your results. Can you reject the null hypothesis H0: β1 = 0? It is observed that x1 and x2 cannot be simultaneously significant in the model in (c). What is this implied?



         
加QQ：99515681  WX：codinghelp
