# Deep-neural-network-step-by-step
In this project, I have built a deep neural network including forward propagation and backward propagation without using any libraries.


The key objective of this project is to develop an intuition of the over all structure of a neural network. 

### The various steps involved in building deep neural networks include:

1. Initialize the parameters for a two-layer network and for an  LL -layer neural network.
2. Implement the forward propagation module (shown in purple in the figure below).
  * Complete the LINEAR part of a layer's forward propagation step (resulting in  Z[l]Z[l] ).
  * We give you the ACTIVATION function (relu/sigmoid).
  * Combine the previous two steps into a new [LINEAR->ACTIVATION] forward function.
  * Stack the [LINEAR->RELU] forward function L-1 time (for layers 1 through L-1) and add a [LINEAR->SIGMOID] at the end (for the final layer  LL ). This gives you a new L_model_forward function.
  * Compute the loss.
  * Implement the backward propagation module (denoted in red in the figure below).
  * Complete the LINEAR part of a layer's backward propagation step.
  * We give you the gradient of the ACTIVATE function (relu_backward/sigmoid_backward)
  * Combine the previous two steps into a new [LINEAR->ACTIVATION] backward function.
  * Stack [LINEAR->RELU] backward L-1 times and add [LINEAR->SIGMOID] backward in a new L_model_backward function
3. Finally update the parameters.

#### Pictorial representation of various steps in constructing deep neural networks:

![Alt Text](https://raw.githubusercontent.com/deepu2010/Deep-neural-network-step-by-step/master/Methodology.JPG)


This project is part of my deep learning specialization course from deeplearning.ai. 

**The key objectives in this notebook is to:**

  * Construct neural network without using any libraries
    * Compute forward propogation
    * Compute Loss
    * Compute backward propogaton
    * Update weights
  * Build a deep learning model to classify cat images.
  * Compare the accuracy of deep learning model with other models built using libraries.
 


#### Neural Network Built:

During my coursework, I have learnt a general methodology to build a Neural Network. The general methodology is as follows:

1. Define the neural network structure ( # of input units,  # of hidden units, etc). 
2. Initialize the model's parameters
3. Loop:
    - Implement forward propagation
    - Compute loss
    - Implement backward propagation to get the gradients
    - Update parameters (gradient descent)

![Alt Text](https://raw.githubusercontent.com/deepu2010/Planar-data-classification/master/planar%20data.JPG)

#### Output Achieved

![Alt Text](https://raw.githubusercontent.com/deepu2010/Planar-data-classification/master/Hidden%20layer%205.JPG)

#### Key activities included in this project

1. Before building my own neural network, I have built a logistic regression machine learning model but I was able to achieve only **47% accuracy**

2. Then, I built a neural network model with a single hidden layer with 4 units, the accuracy is much improved. **Achieved accuracy = 90%**

3. Using trail and error method, I tried adding hidden layers from 1 to 20, based on those observations, I found my model with 5 hidden layers works the best. **Achieved accuracy = 91.5%**

#### Deep Learning Model details:

1. My model can be represented as,

[LINEAR -> TANH] × (L-1) -> LINEAR -> SIGMOID

2. Cost function: **Cross entropy loss functon**
3. Number of hidden units: 5


