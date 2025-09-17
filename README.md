# Simple Neural Network Function Approximation

This repository contains the implementation of a simple 3-layer neural network to approximate the function:  
**f(x) = exp(-sin(x²)/2) + x**

The neural network is implemented from scratch using **NumPy** and runs in **Google Colab**.

---

## ✅ Project Overview

The task is to train a neural network using **Gradient Descent** to approximate the target function.  
- Input: Scalar value `x`  
- Output: Scalar prediction `ŷ`

### Network Structure:
- 3 layers (1 neuron per layer)
- Activation function: **tanh**
- Loss function: **Mean Squared Error (MSE)**

---

## ✅ Key Features

- Manual implementation of forward and backward propagation
- Training and test dataset generation
- Visualization of the true function vs predicted function
- Training and test error reporting

---

## ✅ How to Run

1. Open [Google Colab](https://colab.research.google.com).
2. Upload the notebook `Simple_Neural_Network_Assignment.ipynb`.
3. Run all the cells step by step.
4. Observe the training progress, loss curve, function approximation plot, and final error metrics.

---

## ✅ Results Example

- Final Training MSE: ~7.6379  
- Final Test MSE: ~10.8729  

The plotted graph shows the comparison of:
- True function (green line)
- Neural Network Prediction (blue dashed line)
- Training Data (orange dots)
- Test Data (red crosses)

---

## ✅ Conclusion

This project shows that a very small neural network (3 neurons) can roughly approximate a complex function but does not perform well enough due to limited capacity.  
Using **tanh activation** worked better than ReLU for this task since the target function is smooth and continuous.

---

Feel free to clone and experiment with the code!
