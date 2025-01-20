# Data-Analytics-Lab

# Question 1
The current implementation uses a fixed number of epochs (epochs=1000) as the convergence criterion. The gradient descent algorithm iterates for the specified number of epochs, regardless of whether the model has converged.

To improve the convergence criterion, we can implement an early stopping mechanism based on the change in the loss function (Mean Squared Error). For example, we could stop the training if the change in MSE between consecutive iterations falls below a small threshold.

# Question 2

Advantage of Averaging the Cost

1. Reduced Gradient Variance: Smoother gradients lead to more stable and consistent updates.
2. Better Generalization: Minimizes overfitting by reducing the impact of noise or outliers.
3. Improved Convergence: Smoother cost function enables stable and faster convergence.
4. Scalability: Handles large datasets more efficiently by averaging individual data point influences.
5. Consistent Learning Rate: Prevents drastic changes in learning rate, ensuring steady progress.
