# digit_recognition
A Handwritten digit classification built from a Neural Network from scratch.

# Motivation for the project
The idea of implementing a neural network from scratch came to me while I was working through Prof. Andrew Ng's Machine Learning course on Coursera. A lot of concepts involved in neural networks made intuitive sense to me, but I felt I could do more on the mathematical background of it. Specifically, I wanted to get an idea of how computations can be vectorized with different activation and cost functions.

# Concepts Used 
This project uses the Leaky Rectified Linear Unit (LReLU) and the Softmax functions as activation functions for the hidden layers and output layer (respectively), and the Cross-Entropy Loss (or Log Loss) function as the cost function. 
The optimization function is Mini-batch Stochastic Gradient Descent (mini-batch SGD), and the partial derivatives are computed using Backpropagation.
Furthermore, digits also uses preprocessing techniques such as deskewing on the MNIST dataset. Images drawn by the user undergo preprocessing as well, with additional steps such as normalization.

Aside from implementation, I also manually derived the vectorized formulae for the partial derivatives primarily using dimensional analysis.

# Major Technologies Used
1. Python 3
2. NumPy
3. MatPlotLib
4. SciPy
5. Pillow
