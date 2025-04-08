# Linear regression Exercise 

 This Exercise involves the use of multiple linear regression on the
 Auto data set.
 
 1.  Produce a scatterplot matrix that includes all of the variables
 in the data set.
 2.  Compute the matrix of correlations between the variables using
 the function cor(). You will need to exclude the name variable, cor()
 which is qualitative.
 3.  Use the lm() function to perform a multiple linear regression
 with mpg as the response and all other variables except name as
 the predictors. Use the summary() function to print the results.
 Comment on the output. For instance:
  - Is there a relationship between the predictors and the re
sponse?
  - Which predictors appear to have a statistically significant
 relationship to the response?
  - What does the coefficient for the year variable suggest?
 4.  Use the plot() function to produce diagnostic plots of the linear
 regression fit. Comment on any problems you see with the fit.
 Do the residual plots suggest any unusually large outliers? Does
 the leverage plot identify any observations with unusually high
 leverage?
 5.  Use the * and : symbols to fit linear regression models with
 interaction effects. Do any interactions appear to be statistically
 significant?
 6.  Try a few different transformations of the variables, such as
 log(X), √X, X2. Comment on your findings
