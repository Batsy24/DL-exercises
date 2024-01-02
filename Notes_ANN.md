# Artifical Neural Networks: notes for the future me 

ANNs are pretty much the most basic neural networks you can have other than maybe perceptrons which are pretty much just ANNs with one layer + one node. 

## Forward Propagation
The process of feeding the Inputs forward into the network. Simply a weighted sum with a bias added. What does allat mean? You take the inputs from the *input layer* then, multiply them all with a randomly initialised value assigned to them, called a weight, and then you add a bias. We'll get to the bias later. All of this is done using matrices/vectors.

$W . X + B = Y' $

where:\
$W$ is the weight matrix\
$X$ the inputs\
$B$ the bias\
and $Y'$ the output

this output is then passed through a **Non Linear Activation Function**. More on these in a minute, but its basically any kind of non linear function. I'll use $\sigma$ (sigmoid) as a common example function throughout these notes. 

$Y = \sigma(Y')$

$Y$ is the net output for this layer and becomes the *input* for the next layer. 



### Activation Functions
Activation Functions are essential to neural nets. Basically, they add non lineraity to your model. Take away the activation function and notice how your forward prop equation just becomes  $y = m.x + c$  which is the equation for a straight line. 

Real world data is hardly ever linear, this function makes sure that your network has the ability to generalise to a non linear dataset.


## Implementation

## Backward Propagation
### Loss Functions
### Gradient Descent
### Implementatio

## Metrics and Hyperparameters
