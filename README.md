# residual-vs-plain-gradients

This project demonstrates the effect of residual (shortcut) connections on gradient flow in deep fully connected neural networks using PyTorch. It compares the magnitude of gradients in each layer with and without residual connections after a single backward pass.

---

## What It Shows

- A simple 5-layer fully connected network (`Linear` layers without bias)
- Forward pass includes ReLU activations
- Configurable shortcut (residual) connections
- Measures and prints the mean absolute gradient for each layer's weights
- Demonstrates how residual connections mitigate vanishing gradients


