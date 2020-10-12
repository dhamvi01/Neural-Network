# Neural-Network

a simple neural network consists of interconnected neurons transferring information to each other. Each neuron multiplies its input with its weight(s), applies the activation function on the result, and passes its output on to other neurons. With the help of examples in the training process, a neural network adjusts its weights such that it correctly classifies an unseen input.

A neural network consists of three main layers:

  - input layer: the initial layer of the network which takes in an input.
  - hidden layer(s): the middle optional layer(s) needed for complex tasks.
  - output layer: the final layer of the network which gives the output.

The following are some important functions that will be used in the implementation:

  - activation function: 1/(1+e^x)1/(1+e​x)
  - error function: (target - output)^2 /2
  - derivate of the error function: -(target - output)
  - partial derivative of the activation function: output * (1-output)

Let's build the Simple NN.
