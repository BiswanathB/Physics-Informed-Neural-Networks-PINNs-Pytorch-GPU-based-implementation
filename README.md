This repository presents a GPU-based PyTorch implementation of Physics-Informed Neural Networks (PINNs) to solve the one-dimensional Burgers’ equation. The project focuses on combining deep learning with physical laws to accurately model nonlinear partial differential equations.

The implementation includes different loss function strategies used in PINNs. First, a standard loss formulation is used, where the total loss is defined as a simple linear combination of data loss and physics-based residual loss. This helps the model learn both from given data points and the governing differential equation.

Second, a weighted loss strategy is implemented, where different components of the loss function are assigned adaptive or fixed weights. This approach improves training stability and helps balance the influence of boundary conditions, initial conditions, and PDE residuals.

The code is fully implemented using PyTorch with GPU support for efficient training. The repository also includes visualization of the predicted solution and comparison with exact solutions to evaluate model performance.

This project is useful for understanding how PINNs work in practice, especially for solving nonlinear fluid flow problems, and for exploring different loss balancing techniques in deep learning-based PDE solvers.
