# Simple-Linear-Regression

Dataset Used:
Salary data

YearsOfExperience	Salary
0	1.1	39343
1	1.3	46205
2	1.5	37731
3	2.0	43525
4	2.2	39891


Independent Variable:Years Of Experience
Dependent Variable:Salary
So,here years of experience is the feature and salary is the label.

Feature Engineering  used:
To check for null values like NaN(Not a number):
the isNull() function is used .To know how many null values are present use the sum() function on the isNull() function

Linear Regression is the simplest kind of regression that tries to fit a straight line on the train data.
The LinearRegressor is trained using the train dataset after splitting with the best random state within 2000.
The linear regerssor is used to predict on x_test data to find the predicted y value.The predicted y is compared with the y_test (known) values to find the accuracy of prediction.
Here,we have used R2 score and the mean squared error to find the accuracy of the prediction of salary using years of experience.

