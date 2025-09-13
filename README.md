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

Visualization
Regression Fit Plot
Original noisy data points are shown as scatter plot.
Regression lines from:
Closed-form solution (red solid line)Gradient Descent (green dashed line)Both lines nearly overlap, showing consistency between methods.Loss Curve Plot
Displays MSE versus iterations for gradient descent.Shows a smooth decrease, confirming convergence.

Gradient Descent:
Initialized parameters as [0, 0]
Learning rate = 0.05
Iterations = 1000
Tracked Mean Squared Error (MSE) over iterations
Plotted both the regression lines and the loss curve to visualize convergence.

5. Results & Comparison
Both methods produce very similar results:
Closed-form solution: Intercept ≈ 3.02, Slope ≈ 3.99
Gradient Descent: Intercept ≈ 3.01, Slope ≈ 3.98
Confirms that gradient descent converges to the same solution as the Normal Equation when the learning rate is chosen properly.


