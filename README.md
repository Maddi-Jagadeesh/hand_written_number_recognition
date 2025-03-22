Handwritten Digit Classification (MNIST)

Overview

This project involves building a neural network model to classify handwritten digits from the MNIST dataset. 
The dataset consists of 60,000 training images and 10,000 testing images of digits (0-9). 
The goal is to create a simple yet effective model that can accurately recognize and classify these digits.

Dataset

MNIST Dataset: A collection of grayscale images of handwritten digits, each of size 28x28 pixels.
Classes: 10 (Digits 0-9)
Training Data: 60,000 images
Testing Data: 10,000 images

Model Architecture

A fully connected neural network (ANN) was used for classification.
The model consists of multiple dense layers with activation functions to learn patterns in the input data.
The final layer uses a sigmoid activation function to predict the digit.

Preprocessing

The images were normalized by scaling pixel values to the range [0,1].
The dataset was reshaped for compatibility with the model.
Training and Evaluation
The model was trained on the MNIST dataset using an appropriate loss function and optimizer.
Accuracy was used as the primary evaluation metric.
The trained model was tested on unseen data to measure performance.

Results

The model achieved a reasonable accuracy in classifying handwritten digits.
A confusion matrix was used to analyze misclassifications and improve the model further.

Conclusion

This project demonstrates the effectiveness of artificial neural networks (ANNs) for digit classification. 
Future improvements could include using convolutional neural networks (CNNs) for better accuracy and performance.

Author: Maddi Jagadeesh 
