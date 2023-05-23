**Implementation of Various Optimizers for Linear Regression**

This repository contains an implementation of different optimization algorithms from scratch using Python and NumPy. The focus of this project is to apply these optimizers to achieve linear regression on a given set of data points. The following optimizers have been implemented:

1. **Gradient Descent Variants**:
   - Batch Gradient Descent: The optimizer that updates the model parameters based on the average gradient of the entire training set.
   - Mini-Batch Gradient Descent: Similar to batch gradient descent, but updates the parameters based on a randomly selected subset (mini-batch) of the training set.
   - Stochastic Gradient Descent: Updates the parameters after each individual training sample, rather than using batches or the entire training set.

2. **Momentum**: An optimizer that adds a momentum term to the parameter updates, which helps accelerate convergence and overcome local minima.

3. **Nesterov Accelerated Gradient (NAG)**: A variant of momentum that improves the momentum update by considering the gradient ahead in the direction of momentum.

4. **Adagrad**: An optimizer that adapts the learning rate for each parameter based on their historical gradients, giving more weight to infrequent parameters.

5. **RMSProp**: An optimizer that uses an adaptive learning rate for each parameter. It accumulates the squared gradients and adjusts the learning rate based on the root mean square of these accumulations.

6. **Adam**: A popular optimizer that combines the benefits of momentum and adaptive learning rates. It maintains per-parameter learning rates and adaptive momentum values.

7. **BFGS (Broyden-Fletcher-Goldfarb-Shanno)**: A quasi-Newton optimization method that approximates the inverse Hessian matrix to iteratively update the model parameters.

Each optimizer has been implemented with the goal of optimizing the linear regression model on the given dataset. The implementations utilize vectorized computations using NumPy arrays to achieve computational efficiency. The algorithms support customizable learning rates, batch sizes, and other hyperparameters to allow flexibility in experimentation.

The repository includes detailed documentation and code comments for each optimizer implementation. Additionally, the repository provides examples and usage instructions for applying the optimizers to perform linear regression on various datasets.
