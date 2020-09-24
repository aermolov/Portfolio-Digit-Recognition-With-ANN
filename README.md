# Digit recognition with ANN from scratch

## This notebook contains implementation of artificial neural network for classical problem of handwritten digit recognition using plain python without any neural network libraries.
## The dataset is the MNIST dataset with 60000 training examples and 10000 test examples. Each training and test example is the grey-scaled image of 28x28 pixels.
## The network has following tunable parameters:
* Number of hidden layers
* Number of neurons in eah hidden layer
* Cost function "Quadratic" or "Cross-entropy"
* Activation function of the output layer can be "Sigmoid" or "Softmax" (activations of hidden layers is always "Sigmoid")
* Mini-batch size
* Learning rate
* Regularization parameter
## The accuracy on the test set reached 97.5% in the best run with following parameters of the network:
* Two hidden layers, 100 and 50 neurons in the first and second layers respectevely
* Cost function "Cross-entropy"
* Activation of the hidden layers "Sigmoid", activation of the output layer "Softmax"
* Mini-batch size for stochastic gradient descent 10
* Learning rate 0.1
* Regularization parameter 4
* Training over 60 epochs\
*Accuracy for test set. Epoch 46: 9738 / 10000\
Accuracy for test set. Epoch 47: 9707 / 10000\
Accuracy for test set. Epoch 48: 9715 / 10000\
Accuracy for test set. Epoch 49: 9725 / 10000\
Accuracy for test set. Epoch 50: 9734 / 10000\
Accuracy for test set. Epoch 51: 9739 / 10000\
Accuracy for test set. Epoch 52: 9734 / 10000\
Accuracy for test set. Epoch 53: 9720 / 10000\
Accuracy for test set. Epoch 54: 9738 / 10000\
Accuracy for test set. Epoch 55: 9721 / 10000\
Accuracy for test set. Epoch 56: 9750 / 10000\
Accuracy for test set. Epoch 57: 9743 / 10000\
Accuracy for test set. Epoch 58: 9739 / 10000\
Accuracy for test set. Epoch 59: 9735 / 10000*\

To run the code
- Download "main" notebook form this repository
- Download the classical handwritten digits MNIST datasets from:
http://yann.lecun.com/exdb/mnist/
- Unpack all 4 files to the same directory where you have "main" notebook
