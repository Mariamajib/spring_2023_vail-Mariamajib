# Regression Loss Functions

## Topics covered in today's module
* Mean Squared Error
* Mean Absolute Error
* Mean Squared Logarithm Error

## Main takeaways from doing today's assignment
* Loss function is an indicator of machine learning model performance based on how the model's decisions are.

* Loss function defines what a good prediction is and is not which shows why choosing the right loss function is very crucial.

* Types of loss function
  * Regression Loss Function
  * Classification Loss Function
  
* Regression loss function describes the difference between the values that a model is predicting and the actual values of the labels. This loss function is known as error function or the error formula.

* Examples of regression loss function
  * L1 Loss (Mean Absolute Error)
  * L2 Loss (Mean Square Error or Quadratic Loss)
  * Huber Loss
  * Quantile Loss
  * Log Cosh Loss

* Mean Square Error (MSE) is measured as the average of squared difference between predictions and actual observations.

*  Mean Square Error (MSE) is likely to favour larger errors due to its squaring operation having increased effect on loss function so it is used when minimizing large errors are of high importance.                     

* Mean Absolute Error (MAE) is measured as the average of the sum of absolute differences between predictions ad actual observations.

* Mean Absolute Error (MAE) needs more complicated tools such as linear programming to compute the gradients and it is more robust to outlier since it does not make use of square.

* Mean Absolute Error (MAE) is used when giving all errors equal importance.

* Mean Square Logarithmic Error (MSLE) is th relative difference between the true and the predicted values.

* Mean Square Logarithmic Error (MSLE) treats small differences between small true and predicted values approximately the same as big differences between large true and predicted values.

* We add 1 to the outputs before passing it through log() because log(0) is undefined and the values of x and y can be 0.

* Mean Square Logarithmic Error (MSLE) is used to balance between favouring large errors and avoiding increased effect of square operations in MSE.

## Challenging, interesting, or exciting aspects of today's assignment
* It was interesting to learn about the importance of loss function in Machine Learning Model performance, different types of regression loss functions, their funtions, and when it is appropriate to make use of them to get the desired results. 

## Additional resources used 

