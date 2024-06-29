# Optimization Algorithms in Deep Learning
1. Gradient Descent (GD)
Gradient Descent is a first-order optimization algorithm used to minimize a function by iteratively moving towards the steepest descent, as defined by the negative of the gradient. It’s the foundation of many other optimization techniques.

2. Momentum
Momentum is an extension of Gradient Descent that helps accelerate convergence by considering the past gradients to smooth out the updates. It helps in navigating the ravines and avoiding oscillations, leading to faster convergence.

3. RMSprop
RMSprop (Root Mean Square Propagation) is an adaptive learning rate method that adjusts the learning rate for each parameter. It divides the learning rate by an exponentially decaying average of squared gradients, which helps in dealing with the vanishing and exploding gradient problems.

4. Adam
Adam (Adaptive Moment Estimation) combines the advantages of both Momentum and RMSprop. It computes adaptive learning rates for each parameter and maintains two moving averages of the gradient and the squared gradient. This makes Adam particularly effective for large-scale and sparse data.

5. Newton’s Method (Second Order)
Newton’s Method is a second-order optimization technique that uses the Hessian matrix to incorporate curvature information. It can converge faster than first-order methods by taking into account the second derivative of the loss function. However, it is computationally expensive and often impractical for large-scale problems.
