# Hand-Written-Digit-Recognizer
 ## Import Libraries
In this notebook I have created a model which recognize hand weitten digits.
## Load Dataset
The MNIST database (Modified National Institute of Standards and Technology)- its a inbuilt dataset in tensorflow
The Modified National Institute of Standards and Technology dataset is abbreviated as MNIST and is made up of various types of data. 
The dataset contains 70,000 handwritten single digits between 0 and 9 on 28 pixel grayscale images

## Normalization of Input Data
Normalization helps get data within a range and reduces the skewness which helps learn faster and better .
it increases computatoon speed.Image pixel size is  0 to 255 ,to normalize we divide with 255 to have pixel range in between [0,1]
## Data Visualization
## CNN model
CNN consists of Input layer, convolution layer, Activation function, Pooling layer, fully connected layer.
ReLU (Rectified Linear Unit) Activation Function
Why we use Activation functions with Neural Networks?
It is used to determine the output of neural network like yes or no.The ReLU is the most used activation function in the world right now.Since, 
it is used in almost all the convolutional neural networks or deep learning.
Keras Conv2D is a 2D Convolution Layer, this layer creates a convolution kernel that is wind with layers input which helps produce a tensor of outputs.
First we crearte a keras Squential model and create a convolution layer witrh 32 feature maps at size(3,3).

Batch Normalization:
Batch Norm is a normalization technique done between the layers of a Neural Network instead of in the raw data.It is done along mini-batches instead of the full data set.It serves to speed up training and use higher learning rates, making learning easier.

Softmax is a mathematical function that converts a vector of numbers into a vector of probabilities, where the probabilities of each value are proportional to the relative scale of each value in the vector.

The Adam optimizer makes use of a combination of ideas from other optimizers.Stochastic optimization is the process of optimizing an objective function in the presence of randomness.Optimization is an important process which optimize the input weights by comparing the prediction and the loss function.Metrics is used to evaluate the performance of your model.
Similar to loss function, metrics also accepts below two argument

## Web-Application of this Model using gradio package
Gradio - open source python library to   build  web appliction





























