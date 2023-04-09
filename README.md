# MNIST

In this project I use a Convolutional Neural Network (CNN) on the famous MNIST dataset!

## MNIST dataset

The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. (Wikipedia)

## CNNs

Convolutional neural networks (CNNs) are a type of neural network based on the extraction of features. The model detects these features through a process called convolution. Then these features are downsampled (reduced in size to save memory) using a process called pooling. This process of convolution and pooling is repeated serveral times, with the result being flattened and inputted into a feed-forward dense ANN (Artificial Neural Network), which outputs a final result.

CNNs have a wide range of applications especially in computer vision. Object recognition, medical imaging and autonomous driving all benefit from the use of CNNs.

If you want to learn more, check out my [blog post](https://rablog.vercel.app/posts/convolutional-neural-networks)!

## Project Overview

Here is an overview of the files contained within the project:
- *MNIST.ipynb*: this is the notebook from which we process the datasets, fit the CNN, and perform inference on the testing dataset
- *train.csv*: the MNIST training dataset
- *test.csv*: the MNIST test dataset
- *predictions.csv*: the predictions generated from the model inference

Hope you enjoy! Please don't forget to star the repository too!
