# MNIST Neural Network from Scratch

This project demonstrates how to build and train a simple neural network from scratch (using only NumPy) to classify handwritten digits from the [MNIST dataset](http://yann.lecun.com/exdb/mnist/).

## Features

- Loads and preprocesses the MNIST dataset from raw binary files
- Implements a two-layer neural network (one hidden layer with ReLU, output layer with Softmax)
- Trains the network using forward and backward propagation
- Evaluates accuracy on both training and test sets
- Visualizes predictions and random samples

## How to Use

1. **Download the MNIST dataset**  
   Download the following files and place them in the project directory:
   - `train-images-idx3-ubyte`
   - `train-labels-idx1-ubyte`
   - `t10k-images-idx3-ubyte`
   - `t10k-labels-idx1-ubyte`

2. **Open and run the notebook**  
   Open `Do it.ipynb` in Jupyter Lab or VS Code and run the cells in order.

3. **Experiment**  
   - Change the number of hidden units, learning rate, or number of iterations.
   - Try visualizing different predictions.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- Jupyter Lab or VS Code (recommended for running the notebook)

## Credits

Inspired by:  
[![IMAGE ALT TEXT HER](https://img.youtube.com/vi/w8yWXqWQYmU/0.jpg)](https://www.youtube.com/watch?v=w8yWXqWQYmU)
---

Feel free to fork, modify, and experiment!
