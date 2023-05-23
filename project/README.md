
**Task 1: Multivariable Linear Regression with Adam (Mini-Batch Version)**

This project focuses on implementing and training a multivariable linear regression model using the Adam (Mini-Batch Version) algorithm. The main objectives and requirements for this task are as follows:

1. **Data and Implementation Check**: Utilize the provided dataset file to test the implementation of the Adam algorithm for training the linear regression model.

2. **Achieve High R2-Score**: Ensure that the trained model achieves an R2-Score greater than 0.9, indicating a strong level of prediction accuracy.

3. **Plotting Curves**: Generate the following curves to visualize the training process and model performance:
   - Loss vs. iterations: Plot the loss function's progression over the training iterations.
   - Loss vs. each parameter: Plot the loss function's variation with respect to each model parameter (theta 0, theta 1, etc.).

4. **Hyperparameter Tuning**: Select appropriate hyperparameters to attain the desired accuracy for the model. Experiment with different values and configurations to optimize the model's performance.

5. **Vectorized Implementation**: Implement the algorithm using vectorization techniques, ensuring that calculations are performed efficiently as matrix-vector multiplications. This approach enhances computation speed and improves performance.

6. **Stop Conditions**: Incorporate stop conditions to terminate the training process. Implement two conditions:
   - Gradient < 0.001: Stop the training when the gradient magnitude becomes smaller than 0.001.
   - Cost Convergence Check: Monitor the convergence of the cost function and halt the training if further iterations do not yield significant improvements.

**Task 2: Multivariable Linear Regression with BFGS Optimizer**

For this task, the focus is on repeating the previous multivariable linear regression experiment, but this time using the BFGS optimizer instead of Adam. All the requirements from Task 1 also apply to Task 2. Additionally, you need to compare the results obtained from both tasks and draw conclusions based on the comparison.
