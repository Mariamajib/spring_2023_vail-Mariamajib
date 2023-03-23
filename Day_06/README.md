# Classification Loss Functions

## Topics covered in today's module
* Kullback Leibler Divergence Loss
* Binary Cross-Entropy
* Categorical Cross-Entropy
* Sparse Categorical Cross-Entropy

## Main takeaways from doing today's assignment
* Classification Loss Function represent the price paid of predictions in problems of indentifying which category a particular observation belongs to.

* Examples of classification loss function
  * Log loss
  * Focal loss
  * Exponential loss
  * Hinge loss
  * Relative entropy loss
  
* Kullback Leibler Divergence Loss is a measure of how a distribution varies from a reference distribution or a baseline distribution. 

* A Kullback Leibler Divergence Loss of zero means that both the probability distributions are identical.

                                            𝐾𝐷𝐿(𝑝||𝑞)=∫𝑥𝑝(𝑥)log𝑝(𝑥)𝑞(𝑥)𝑑𝑥 

* Cross-entropy is a measured by calculating the difference between two probability distributions.

* Kullback Leibler Divergence calculates the relative entropy between two probability distributions, whereas cross-entropy calculate the total entropy between the distributions.

* Binary Cross Entropy is a loss function that is used in binary classification tasks which are only two choices (yes or no, A or B, 0 or 1, left or right).

                                           𝐵𝐶𝐸=−1𝑁∑𝑖=1𝑁𝑦𝑖⋅log(𝑝(𝑦𝑖))+(1−𝑦𝑖)⋅log(1−𝑝(𝑦𝑖)) 
                                           
* Multi-class classification problem deal with mutually exclusive classes which needs categorical cross entropy loss function.  

* Multi-label classification deal with non-exclusive classes where an input may belong to more than one class and this needs binary cross entropy.

* Categorical cross entropy can be used in all kind of classification problem while Sparse categorical cross entropy can be used wnen each input belongs to single class only having all 0's except just a single element 1 (one-hot-encoding).
 


## Challenging, interesting, or exciting aspects of today's assignment
* It was interesting learning about the application of classification loss function  becuase we discussed classification loss function under types of loss functions in the previous assignment.

## Additional resources used 

