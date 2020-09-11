# digit_recognition_with_ANN

This notebook contains implementation of artificial neural network for classical problem of handwritten digit recognition using plain python without any neural network libraries.
The dataset is the MNIST dataset with 60000 training examples and 10000 test examples. Each training and test example is the grey-scaled image of 28x28 pixels.
Using two hidden layers, the accuracy on the test set of 97.35% achieved over the training through 60 epochs with mini-batch size of 10 samples and sigmoids as activation function in each layer
Cost function - root mean square error, activation functions - sigmoid.

To run the code
- download "main" notebook form this repository
- download the classical handwritten digits MNIST datasets from here:
http://yann.lecun.com/exdb/mnist/
- unpack all 4 files to the same directoru where you put "main" notebook
