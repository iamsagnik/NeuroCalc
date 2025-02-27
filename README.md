# NeuroCalc
A neural network project to simply understand the backpropagation and underneath working of a neural network. It is a lightweight autograd engine inspired by Andrej Karpathy's original project. It enables automatic differentiation using computational graphs and backpropagation, allowing the training of simple neural networks from scratch.

## Features
- Scalar-based autograd engine
- Computational graph for gradient tracking
- Backpropagation for gradient computation
- Basic neural network implementation
- Simple optimization using gradient descent

## Usage
You can experiment with the autograd engine and train a simple neural network as follows:

```python
from micrograd import Value

a = Value(2.0)
b = Value(-3.0)
c = Value(10.0)
y = a * b + c  # Example computation
y.backward()    # Compute gradients

print(a.grad, b.grad, c.grad)  # Display gradients
```
## Installation
To use this implementation, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/micrograd-implementation.git
```
