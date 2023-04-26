# Digit-Recognization

This code is for building a deep learning model using convolutional neural network (CNN) for the Digit Recognizer problem on Kaggle. The dataset used is the MNIST dataset, which contains images of handwritten digits.

The code imports the required libraries, loads the training data, pre-processes the data, builds and trains the CNN model, evaluates the model using validation data, plots the accuracy and loss graphs, loads and pre-processes the test data, and finally makes predictions on the test data and saves the results to a CSV file.

The CNN model architecture consists of two sets of convolutional and pooling layers followed by a fully connected layer and an output layer with 10 neurons (one for each digit).

The model is trained for 30 epochs with a batch size of 32 and the RMSprop optimizer is used to minimize the categorical cross-entropy loss function.

The accuracy and loss graphs show that the model has good performance on both the training and validation sets, and there is no overfitting.

The model is saved in the "digit.h5" file.
