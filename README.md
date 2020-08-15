# Convolutional_Neural_Network using NumPy
This repository contains Python code (without the use of any packages, apart from NumPy) for Convolutional Neural Networks. A user can enter any number of convolutional and pooling layers at whatever order. This CNN is a softmax classifier using cross-entropy loss as the loss function. The master branch is the code for Stochastic Gradient Descent and the feature/Adam branch is the code for Gradient Descent with Adam Optimisation. The user can however add only one Fully Connected Layer.

We initialised weights through random number initialisation. The Rectified Linear Unit is used as the activation function and parameter sharing is enabled for this CNN. Cross-Entropy loss has been used for the loss function, without paramter regularisation.

## Results for MNIST Data
For testing our CNN with MNIST data, we used one Conv layer (receptive field: 3, filters: 10, stride length: 1), one Pooling layer (receptive field: 2) and one FC layer. Training size: 1000 images, testing size: 1000 images, 10 epochs, learning rate: 0.005. 
1. SGD gave an accuracy of %.

2. Adam gave an accuracy of %.

3. Keras for the same configuration gave an accuracy of %.

## Future Updates
1. The option to add any number of FC Layers. 

2. Inclusion of Biases.

3. Parameter regularisation in loss function.
