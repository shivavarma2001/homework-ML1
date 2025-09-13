# homework-ML1
Implement-Gradient-Descent-for-Linear-Regression

#700766407

indukuri shanmukha shiva kesava varma

Description :
This assignment focuses on implementing linear regression using two different approaches: the closed-form solution (Normal Equation) and gradient descent. The goal was to compare both methods and understand how they perform on a synthetic dataset.

Dataset :
I generated 200 data points using the equation: y = 3 + 4x + ,E where E is Gaussian noise and x is randomly sampled from the range [0, 5].

Implementation
Closed-form solution: Used matrix operations with the Normal Equation to directly compute optimal parameters.

Gradient Descent:
Initialized parameters as [0, 0]
Learning rate = 0.05
Iterations = 1000
Tracked Mean Squared Error (MSE) over iterations
Plotted both the regression lines and the loss curve to visualize convergence.

Results
Both methods produced very similar results for the intercept and slope, confirming that gradient descent successfully converged to the same solution as the closed-form method. The loss curve showed smooth and consistent improvement over time.
