# Optimization

## Topics covered in today's module
* Optimization
* Gradident Descent
* Optimizers(SGD, ADAM, etc.)

## Main takeaways from doing today's assignment
* Optimization algorithm as a program or series of instructions that try to find the best item when compared to other items using a given method of comparison or metric with the aim to minimize the loss/cost function.

* Types of Optimizers
  * Gradient Descent 
    * Batch Gradient Descent (BGD)
    * Stochastic Gradient Descent (SGD)
    * Mini-batch Gradient Descent (MB-SDG) 
  * Stochastic Gradient Descent (SGD) with momentum
  * Nesterov Accelerated Gradient (NAG)
  * Adaptive Optimization
    * Adaptive Gradient (AdaGrad)
    * AdaDelta
    * RMSprop
    * Adam
    
* Gradient Gradient Descent (BGD) is an interative process that finds the parameters or coefficients of a function where the function has a minimum value.

* Learning rate is a configurable hyperparameter used in the training of neural networks which controls how much to change the model in response to the estimated error each time the model weights are updated. It have small positive value, often between the range of 0.0 and 1.0.

* For small learning rate, updates are small, and optimization is slow which makes the model likely to get stuck into a local minimum or plateau.

* For too large learning rate, updates are large, and optimization is likely to diverge.

* For well chosen learning rates, updates are appropriate, and optimization should converge to a good set of parameters.

* A Loss Functions tells us “how good” our model is at making predictions for a given set of parameters which has its own curve and its own gradients. The slope of this curve tells us how to update our parameters to make the model more accurate.

* First order method gives us information about whether or not our loss is increasing or deacresing in a given direction

* Second order method tells us how much our loss is increasing or decreasing. Second order methods can find a minima in fewer steps, and have less trouble with getting stuck in saddle points.

* Examples of Second order method
  * Newton's method
  * Broyden-Fletcher-Goldfarb-Shanno algorithm (BFGS)
 
  

## Challenging, interesting, or exciting aspects of today's assignment
* It was interesting to learn about the importance of optimization, the different types of optimizers, and how to apply them.

## Additional resources used 
<To be filled>
