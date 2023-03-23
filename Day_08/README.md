# Activation Functions

## Topics covered in today's module
* Introduction to Sigmoid, Tanh, ReLU
* Visualizing how ReLU affects the feature maps
* Vanishing and exploding gradients
* Dying ReLU problem
* Advanced activation functions: Swish, GeLU, SeLU

## Main takeaways from doing today's assignment
* Activation function is a non-linearr function applied by a neuron to introduce non-linear properties in the network which decide whether the certain neuron should be actiivated or not.

* The choice of activation function in the hidden layer controls how well the network model learns the training dataset.

* The choice of activation function in the output layer will define the type of predictions the model can make.

* The most commonly used activation layer for hidden layers are 
  * Rectified Linear Activation (ReLU)
  * Logistics (Sigmoid)
  * Hyberbolic Tangent (Tanh)

* For hidden layers
  * Multilayer Perceptron: ReLU
  * Convolutional Neural Networks: ReLU
  * Recurrent Neural Network: Tanh and/or sigmoid

* The most commonly used activation layer for outlayers are
  * Linear
  * Logistics (Sigmoid)
  * Softmax
 
* For Outer layers
  * Regression 
    * One node, linear activation
  * Classification
    * Binary classification: one node, sigmoid activation
    * Multi-class classification: one node per class, softmax activation
    * Multi-label classification: one node per class, sigmoid activation
* Swidish function is used in neural networks having a depth greater than 40 layers.

* Types of Activation Function
  * Logistic (sigmoid) is a non-linear function also known as squashing function is used as an activation function  in neural networks. It can also be used for hidden layers but mostly used for output layers of a binary classification, where the result is either 0 or 1. Its resullt can be predicted to be 1 if value is greater than 0.5 and 0 therwise. A weighted sum of inputs is passed throughan activation function and this output serves as an input to the next layer.
                                   
                                   𝑆𝑖𝑔𝑚𝑜𝑖𝑑(𝑥) = 1/1 + 𝑒−𝑥 

  * Hyperbolic Tangent (Tanh) is a non-linear function used in hidden layers as an activation function. The function takes any real value as input and outputs values in the range -1 to 1. The larger the input (more positive), the closer the output value will be to 1.0, whereas the smaller the input (more negative), the closer the output will be to -1.0.
  
                                   𝑇𝑎𝑛𝐻(𝑥) = 𝑒𝑥 − 𝑒−𝑥/𝑒𝑥 + 𝑒−𝑥
                                   
  * Rectified Linear Activation (ReLU) is a non function which can easily backpropagate the errors and have multiple layers of neurons neurons being activated.
                                  
                                  𝑅𝑒𝐿𝑈(𝑥) = {𝑥 𝑥 > 0
                                             0 𝑥 <= 0 

                                  𝐿𝑒𝑎𝑘𝑦-𝑅𝑒𝐿𝑈(𝑥) = {𝑥  𝑥 > 0
                                                  α𝑥 𝑥<=0 
                                                  
                                  𝐸𝐿𝑈(𝑥) = {𝑥         𝑥>0
                                            𝛼⋅(𝑒𝑥−1)  𝑥<=0

    *  The reasons of replacing sigmoid and hyperbolic tangent with ReLU consist of:
      
        * Computation saving - the ReLU function is able to accelerate the training speed of deep neural networks compared to traditional activation functions since the derivative of ReLU is 1 for a positive input. Due to a constant, deep neural networks do not need to take additional time for computing error terms during training phase.

        * Solving the vanishing gradient problem: The ReLU function does not trigger the vanishing gradient problem when the number of layers grows. This is because this function does not have an asymptotic upper and lower bound. Thus, the earliest layer (the first hidden layer) is able to receive the errors coming from the last layers to adjust all weights between layers. By contrast, a traditional activation function like sigmoid is restricted between 0 and 1, so the errors become small for the first hidden layer. This scenario will lead to a poorly trained neural network.

  * Softmax is a non-linear function used in the output layer of the classifier while trying to attain the probabilities to define the class of each input. The output for each class is between 0 and 1. It is usually used to handle multiple classes
 
 * Vanishing gradient means the gradients are so small that the learning will be very slow.
 
 * Exploding gradient is when the derivatives are large then the gradient will increase exponentially as we propagate down the model until they eventually explode.

## Challenging, interesting, or exciting aspects of today's assignment
* It was interesting viewing the graphical representations of the various types of acttivation functions and learning their applications. 

## Additional resources used 

