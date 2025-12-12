[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/kavyaajin16/PINN-LiteNet/blob/main/PINN_LiteNet.ipynb)

# PINN-LiteNet

This project implements a Physics-Informed Neural Network (PINN) to solve
a first-order differential equation using deep learning.

## Equation Solved
dy/dx = -y  
y(0) = 1  

Exact solution: y(x) = exp(-x)

## Features
- Physics-informed loss function
- Automatic differentiation (TensorFlow)
- Adaptive training strategy
- No labelled data required

## Technologies Used
- Python
- TensorFlow
- NumPy
- Matplotlib
- Google Colab

## How to Run
1. Open `PINN_LiteNet.ipynb` in Google Colab
2. Runtime → Run all
3. View plots and results

## Author
Kavya Jain  
B.Tech CSE (Artificial Intelligence)
