# Coding-Gradient-Descent-for-LSR
Gradient descent is a optimization algorithm used to minimize the cost function of a linear regression model. In the case of simple linear regression (LSLR), the cost function is the mean squared error (MSE) between the predicted values and the actual values

# Coding gradient descent for LSLR involves initializing the model parameters (i.e. the slope and y-intercept of the line), and then repeatedly updating the parameters in the direction of the negative gradient of the cost function with respect to the parameters. The gradient descent algorithm can be implemented using the following steps:

1. Initialize the model parameters (slope and y-intercept) with some random values.
2. Calculate the predicted values using the current parameter values and the input data.
3. Calculate the cost (i.e. the MSE) by comparing the predicted values to the actual values.
4. Calculate the gradient of the cost function with respect to the parameters.
5. Update the parameters by subtracting the gradient multiplied by a learning rate (a small value used to control the step size of the update).

Repeat steps 2-5 until the cost function stops decreasing or a maximum number of iterations is reached.

Once the algorithm has converged, the model parameters will be the values that minimize the cost function. These parameters can then be used to make predictions on new data.
