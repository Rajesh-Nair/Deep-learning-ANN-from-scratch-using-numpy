# Deep learning ANN model from scratch
Designing a model from scratch help you understand the algorithm and also give you much insights to help you solve practical/real world problems. Though modern day deep learning packages like Tensorflow are quick and efficient, learning from scratch helps you learn the nitty gritty of the model architecture. This GitHUB page is an attempt to understand Artificial Neural Network models by developing it from scratch. 

## Artificial Neural Network design from scratch using numpy (ANN)
Description:
To start with, we will design a neural network that can be parameterized to form shallow or deep neural network. Following are some of the typical parameters that can be tuned.
- Number of layers, units and their activation functions with options of sigmoid, tanh, relu and leaky relu. We can define softmax function for multi class classifier.
- Optimizers like Gradient Descent, Gradient Descent with momentum, RMSprop and Adam
- Batch/Mini batch/Stochastic Gradient
- Learning rate Decay for better optimization
- L2 regularization and Drop out regularization methods

We will create a simple petal dataset to train, predict and form decision boundary. This will help us to understand how much Neuralnet is capable of understanding the nonlinear region where traditional machine learning algorithm struggles.

## Artificial Neural Network design from scratch using tensorflow (ANN)
Next we would build similar network and process the same dataset using tensorflow which will give you a good comparison between 2 methods. Tensorflow frame is fast, efficient and easier to code. One of important highlight is tensorflow finds its own to do backward propagation and update parameters.
**NOTE**: This program is written to compare the approach using numpy with that of tensorflow and that this not an ideal build from scratch code.

## Reference : Andrew Ng's Deeplearning course on coursera
