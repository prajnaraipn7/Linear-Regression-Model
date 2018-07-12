# Linear-Regression-Model
We will use Swedish insurance dataset – called as Auto insurance dataset
X is the total claims
Y is predicting total amount to be paid to all the claims
Problem statement:
 For a new claim(X) how much amount is to be paid(Y)
We follow the below steps:
	1. Calculate Mean and Variance
	2. Calculate Covariance
	3. Estimate Coefficients
	4. Make predictions
	5. Predict Insurance
Calculate Mean and Variance:
Calculate mean and variance of both input and output variables.
	Mean=Sum/Count
Variance is the sum-squared difference of each value from the mean.
Calculate Co-Variance:
Covariance between two groups of numbers describes how those numbers change together.
NOTE: 
•	Correlation tells relationship between two groups of numbers
•	Covariance tells relationship between two or more group of numbers

Covariance = sum ((x (i) - mean(x)) * (y (i) - mean(y)))

Estimate Coefficients:
We must estimate two coefficients in linear regression.
B1 = sum ((x (i) - mean(x)) * (y(i) - mean(y))) / sum( (x(i) - mean(x))^2 )
Which is B1 = covariance(x, y) / variance(x)
B0=mean(x)-B1*mean(y)
Make Predictions:
Once we find coefficients, we can find the predictions. The equation to make predictions with single linear regression is :
			Y=mx+b
We make predictions on test set using the coefficients from training data and test data.
Model Evaluation:
We are finding the error by Root Mean Square Error of the predictions. We are evaluating the model by finding the difference between actual and predicted values.
RMSE =SQRT(sum((y prediction –y actual)^2)/N)
That is RMSE = SQRT(sum(prediction error)^2)/N)
