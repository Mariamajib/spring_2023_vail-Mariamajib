# Regularization

## Topics covered in today's module
* L1/L2 Regularization
* Dropout
* Overfitting
* Underfitting

## Main takeaways from doing today's assignment
* L1 Regularization is where the cost added is proportional to the absolute value of the weights coefficients which is called the "L1 norm" of the weights.
                                    
                                    𝑐𝑜𝑠𝑡=(𝐲−𝐱𝑊)2+λ||𝑊|| 

* L2 regularization is also called weight decay. L2 regularization is where the cost added is proportional to the square of the value of the weights coefficients which is called the squared "L2 norm" of the weights.
 
                                   𝑐𝑜𝑠𝑡=(𝐲−𝐱𝑊)2+λ||𝑊||22 

* Dropout is used to randomly select some nodes and remove them along with all of their incoming and outgoing connections at every iteration.

* To prevent overfitting in neural networks:
  * Get more training data
  * Reduce the capacity of the network
  * Add weight regularization
  * Add dropout
  * Data-augmentation
  * Batch normalization

* To prevent underfitting in neural networks:
  * Get more training data
  * Increase the size or number of parameters in the model
  * Increase the complexity of the model
  * Increasing the training time, until cost function is minimised

## Challenging, interesting, or exciting aspects of today's assignment
It was interesting learning to apply the L1 Regularization and L2 regularization that was discussed as a method to reduce overfitting in the Day 10- Overfitting and Underfitting. 

## Additional resources used 
<To be filled>
