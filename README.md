# Handwritten-Digits-Classification Using Neural Networks

The dataset consists of a training set of 60000 examples and test set of 10000 examples. All digits have been size-normalized and centered in a fixed image of 28*28 size. In original dataset, each pixel in the image is represented by an integer between 0 and 255, where 0 is black, 255 is white and anything between represents different shade of gray. The official training set of 60000 examples is divided into an actual training set of 50000 examples and validation set of 10000 examples.

# Task -
1) Implemented Neural Network (forward pass and back propagation)
2) Incorporated regularization on the weights
3) Used validation set to tune hyper-parameters for Neural Network (number of units in the hidden layer and lambda).

nnObjFunction: compute the objective function of Neural Network with regularization and the gradient of objective function.
nnPredict: predicts the label of data given the parameters of Neural Network.
