# LinearRegression
A bike-sharing provider recently suffered considerable dips in their revenues due to the ongoing Covid19 pandemic and wants to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.¶

Essentially, the company wants to identitfy —
  1) Which variables are significant in predicting the demand for shared bikes.
  2) To create a linear model that quantitatively relates bike demands with respect to variables like weather, day of the week, holiday, temperature etc.
 3)To know the accuracy of the model, i.e. How well those variables describe the bike demands.

We would use Linear Regression to answer above questions.

Liner Regression is one of the most commonly used algorithms in Predictive modelling.
It linearly models the relationship between Target (dependent) variable and one or more independent (explanatory) variables with the help of correlation coefficient and by fitting a linear line/plane to the observed data.
The two type of Linear Regression model:
• Simple Linear Regression
• Multiple Linear Regression.
For simple linear regression, best fit line is defined by:
  Y =mx+b
where m is the slope , b is the intercept, X id the explanatory variable and Y is the dependent variable.
The above equation can also be represented by coefficients:
Y= B0+B1.X
In Multiple Linear Regression, it fits a hyperplane defined by:
  Y=B0+B1.X1+B2.X2+……..Bn.Xn.
Then, linear regression model learns to estimate these coefficients for the representation of data using various techniques. Some of the most common techniques are Ordinary Least Squares and Gradient descent.

The Ordinary Least Squares calculates the best fit line by minimizing the sum of squares of predicted values and actual data points.
Gradient Descent calculates optimal Coefficients using an iterative minimization method which reaches local minima step by step (learning rate).
There are few statistics which help to identify goodness of fit for a Linear Regression model and how accurately our model predicts:
• T-Statistics: If the coefficient is significant or not.
• F-Statistics: Overall model fit is significant or not.
• R-squared: It tells the extent of the fit -how well the straight line describes the variance in the data. Its value ranges from 0 to 1,
Once linear regression model is fit to a group of datasets, examination of the error terms calculated using the actual and predicted values, can help us validate the model and existence of linear relationship based on a few important assumptions:
1. Linear relationship between X and Y.
2. Error terms are normally distributed (not X, Y) .
3. Error terms are independent of each other.
4. Error terms have constant variance (homoscedasticity) .
