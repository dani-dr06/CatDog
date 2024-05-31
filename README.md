# CatDog

The present project provides the training of a Convolutional Neural Network (CNN) for image classification on a subset of the Open Images dataset containing images of dogs and cats.

## Libraries Used
- TensorFlow
- NumPy
- Matplotlib

## CNN Architecture
The initial neural network consisted of 4 convolutional blocks - a convolutional block consisting of a convolutional layer, followed by a batch normalization layer, a max pooling layer, and finally a dropout layer. After these 4 convolutional blocks, the output was flattened, and fed through two fully connected layers, the first of which had a reLU activation function and the last one a sigmoid activation function, since the task is that of binary classification.
