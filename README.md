# Linear Regression
This algorithm learns a model that is a linear combination of features of input example. That means that the algorithm tries to learn the linear relationship between the input features and target variables in the dataset. The model is a linear equation that combines the features in a linear manner to make the predictions about the target variables.

## The process
The aim is to find the best fitting linear relationship between the input features (X) and target variable (y).

## fw,b (x) = wx + b (model equation)
The model starts with some random weights or the cofficient to the linear equation. We want find the optimal value for 'w' and 'b' for our model. The regression model is a line for one dimensional feature vectors, a plane for 2 dimensional feature vectors, and hyperplane for more than 2 features.

## loss function and cost function
The aim is to minimize the loss function and ultimately the cost function.

## (fw,b (xi ) − yi )^2
The above expression is the loss function that measures the loss or penalty for getting prediction that is far from the actual target variable. The average of loss for all the training sample is called cost function. The loss in linear regression is a quadratic function.

## Gradient Descent
To optimize the value of the parameters w and b, we use optimization algorithms like gradient descent. The aim is to reduce the cost function to reach the optimal solution. The algorithm randomly sets the coefficient values to reduce the cost function and does this iteratively to reach the global minima or the minimum cost function. The number of steps taken and how fast the algorithm converges to the minima is determined by the learning rate.

# Gentle introduction to Linear Regression, Decision Tree and Random Forest Regressor
Here, I am using the Graduate Admission 2 dataset from kaggle (https://www.kaggle.com/datasets/mohansacharya/graduate-admissions/code) to predict the chances of admission to grad school based on the student profile and university ranking.
