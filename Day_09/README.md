# Overfitting and Underfitting

## Topics covered in today's module
* Overfitting
* Underfitting
* Data preparation
* Reducing network capacity

## Main takeaways from doing today's assignment
* Overfitting occurs when the neural network is too complex, it will start memorizing the training data instead of having a general understanding of the data.

* Underfitting is a scenario where a data model is unable to capture the relationship between the input and output variables accurately, generating a high error rate on both the training set and unseen data.

* Good Fit Learning curve

   A plot of learning curves shows a good fit if:
    
    * The plot of training loss decreases to a point of stability 
    * The plot of validations loss decreases to a point of stability and has a snall gap with the training loss

* Overfitting Model
 
   A plot of learning curves shows a good fit if:
    
    * The plot of training loss continous to decreases with experience
    * The plot of validation loss decreases to a point and begins increasing again 
    
* Underfitting Model
   
  A plot of learning curves shows a good fit if:
    
    * The cost (loss) function is high and doesn't decrease with the number of iterations, both for the validation and the training curves
    * The training loss remains flat regardless of training
    * The training loss continues to decrease until the end of training 

* For Reducing overfitting:
  
  * Increase more data in the datasets
  * Reduce model complexity by reducing the number of parameters
  * Apply regularization by adding a cost to the loss function for large weights
      
      * L2 and L1 regularization 
      * Use Dropout layers which will randomly remove certain features by seeting them to zero
      * Early stopping

* For Reducing underfitting:
     
     * Train a more complex model( a model with higher value of max depth)
     * Increase the duration of training
     * Eliminate noise from data by using data cleaning techniques 
     * Adjust regularization parameters

## Challenging, interesting, or exciting aspects of today's assignment
* It was interesting  creating an overfitting and underfitting visualizations and learning about how to reducing them.

## Additional resources used 

