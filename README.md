# Deep-neural-network-step-by-step
In this project, I have built a deep neural network including forward propagation and backward propagation without using any libraries. The key goal of this project is to develop an intuition of the over all structure of a neural network. 

**The key objectives in this notebook is to:**

  * Construct neural network without using any libraries
    * Compute forward propogation
    * Compute Loss
    * Compute backward propogaton
    * Update weights
  * Build a deep learning model to classify cat images.
  * Compare the accuracy of deep learning model with other models built using libraries.

### The various steps involved in building deep neural networks include:

1. Initialize the parameters for a two-layer network and for an  LL -layer neural network.
2. Implement the forward propagation module.
  * Complete the LINEAR part of a layer's forward propagation step (resulting in  Z[l]Z[l] ).
  * Compute the ACTIVATION function (relu/sigmoid).
  * Combine the previous two steps into a new [LINEAR->ACTIVATION] forward function.
  * Stack the [LINEAR->RELU] forward function L-1 time (for layers 1 through L-1) and add a [LINEAR->SIGMOID] at the end (for the final layer  LL ). This gives you a new L_model_forward function.
  * Compute the loss.
  * Implement the backward propagation module (denoted in red in the figure below).
  * Complete the LINEAR part of a layer's backward propagation step.
  * Compute the gradient of the ACTIVATE function (relu_backward/sigmoid_backward)
  * Combine the previous two steps into a new [LINEAR->ACTIVATION] backward function.
  * Stack [LINEAR->RELU] backward L-1 times and add [LINEAR->SIGMOID] backward in a new L_model_backward function
3. Finally update the parameters.

#### Pictorial representation of various steps in constructing deep neural networks:

![Alt Text](https://raw.githubusercontent.com/deepu2010/Deep-neural-network-step-by-step/master/Methodology.JPG)


This project is part of my deep learning specialization course from deeplearning.ai. 

#### Deep Learning Model details:

1. My model can be represented as,

[LINEAR -> RELU] × (L-1) -> LINEAR -> SIGMOID

2. Cost function: **Cross entropy loss functon**
3. Number of hidden units: Depending on the requirement



#### Output Achieved

Training accuracy: 0.98

Test accuracy: 0.8

#### Key activities included in this project

1. I built a neural network model with two hidden layer with 4 units, the accuracy is much improved. **Achieved accuracy = 72%**

2. Using trail and error method, I tried adding hidden layers from 1 to 20, based on those observations, I found my model with 4 hidden layers works the best. **Achieved accuracy = 80%**




