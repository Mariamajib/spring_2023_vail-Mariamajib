# Artificial Neural Networks

## Topics covered in today's module
* Introduction to Neural Networks
* Hyperparameters
* Forward Pass
* Backpropagation
* Computing accuracy

## Main takeaways from doing today's assignment

* Types of Layers in Neural Networks
  * First layer - Input layer
  * Layers between first and last layer - Hidden layers
  * Last layer - Output layer

* Initialization of weight is done by assigning random smaller numbers to weight using standard normal distribution to optimize accuracy.

* Randomization is used for model optimization and to prevent "vanishing or exploding" activations and gradients when training the model.

* Properties of Activation energy
  
  * Nonlinear
  * Injective meaning f(x2) = f(x3) implies x2 = x3 
  * Differential and continous
  
* Sigmond activation function is used for two outputs (binary classification) with probability range of 0 and 1 while softmax activation function is used for multi-class classification.

* Rectified linear activation function (RELU) allows models to learn faster and perform better which prevents "vanishing gradients problems".

* ReLU activation function is linear in the positive dimension, but zero in the negative dimension.

* Forward pass is used for prediction and generating loss for backpropogation.

* Backward pass uses the backpropogation algorithm and an optimizer SGD (Stochastic Gradient). It allows changes in the dimensionality and numbers of layers in code.

## Challenging, interesting, or exciting aspects of today's assignment

* It was interesting seeing the application of backward and forward pass. Also, knowing that other python libraries aside from tensorFlow using C help make the training and execution faster

## Additional resources used 
