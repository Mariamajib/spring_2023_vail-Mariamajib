# Convolution Neural Network

## Topics covered in today's module
* Convolution neural network components
* Visualizing kernels
* Visualizing feature maps
* Pooling
* Dropout
* Batch norm

## Main takeaways from doing today's assignment
* Convolution is a filter that passes over an image, process it, and extracts the important features.

* Convolutional Neural Network (CNN or ConvNet) is a class of neural networks that specializes in processing data that has a gridlike topology such as image.

* Filters are neurons in convolutional layer that cover the entire input and look for one feature.

* Receptive field is the restricted region of the visual field.

* Three Layers 
  * Convolutional layer
  * Pooling layer
  * Fully connected layer
  
* The test and the train images are divided by 255 for normalization by bringing all values of datasets to common scales to speed up the learning which lead to faster convergence.

* Each convolutional layer has two sets of weights
  * Block of filters
  * Block of bias values
  
* A simple image has three channels which are red, green, and blue.

* Grayscale images need one input channel to describe them.

* Feature maps (activation maps) are output between layers in the neural network.

* Overfitting is a phenomena that happens when the training data set is not large enough to accomodate the number of features that can theoretically be used classifications/prediction by the neural network built to learn the prediction task.

* Techniques for reducing overfitting 
  * Pooling layer with padding
  * Dropout 
  * Batch Norm
  
* Pooling layer is used to reduce the spatial dimensions (height and width) which can also reduce overfitting.

* Dropout is a regularization method that approximates training a large number of neural networks with different architectures in parallel.

* Dropout layers is used to train remaining active neurones more to minimized error when the model is overfitted which leads to some neuron becoming inactive.

* Batch normalizing layers can be used to improve training speed which is caused by the data in intermediate layers not having connections to its features resulting to negated feature drift when a model has internal covariate shift.

## Challenging, interesting, or exciting aspects of today's assignment
* It was exciting  seeing the visualizations of the datasets and how different neural network architectures interact with them. 

* It was fascinating to see how convolutional neural networks could detect and form images just as the neural networks of the human brain.

## Additional resources used 

