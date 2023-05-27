# American Sign Language Detection with Convolutional Neural Networks
Unleashing the Power of CNNs for Precise American Sign Language Recognition.

This project focuses on training a convolutional neural network (CNN) model to recognize American Sign Language (ASL) letters. The goal is to classify hand gestures representing the letters A-Z (excluding J and Z) using a dataset of grayscale images.

**DATASET** 

The dataset used for training and testing the model is similar in format to the classic MNIST dataset. 

It consists of 27,455 training cases and 7,172 test cases, with each case representing a 28x28 pixel image and a corresponding label.


**GETTING STARTED**

To use this code, follow the steps below:

*Clone the repository:* git clone https://github.com/saikeerthana-narra/American-Sign-Language-Detection-with-CNN.git

*Install the required libraries*

*Download the dataset*

*The training and test datasets can be downloaded from the following links:* 

    Training Dataset
    
    Test Dataset

*Place the downloaded CSV files in the project directory*

*Run the code*


**MODEL ARCHITECTURE**

The CNN model used for this project has the following architecture:

a) Convolutional layers with ReLU activation.

b) Max pooling layers for downsampling.

c) Batch normalization layers for normalization.

d) Dropout layers for regularization.

e) Fully connected layers with ReLU activation.

f) Softmax activation for the output layer.

g) The model is trained using the training data and evaluated on the test data.

h) The training process includes data augmentation techniques such as rotation, zooming, and shifts to improve generalization.


**RESULTS** 

After training the model, the performance on the test data is evaluated. The following results were obtained:

**LOSS: 0.2815**

**ACCURACY: 0.9826**

In this case, the model is achieving a relatively low loss value and a high test accuracy. 

A loss of 0.2815 indicates that the model's predictions have a small deviation from the true values. 

A test accuracy of 0.9826 indicates that the model is correctly classifying or predicting approximately 98.26% of the samples in the test dataset.

These values suggest that the model is performing well and achieving a high level of accuracy on the given task.


**FURTHER IMPROVEMENTS** 

Possible improvements for this project include:

  Experimenting with different architectures or hyperparameters to improve model performance.

  Exploring other data augmentation techniques.

  Training the model on a larger dataset for better generalization.
