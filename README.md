The following python notebook contains my solution for recognizing entities in Triple MNIST dataset using Convolutional Neural Network (CNN).

To recognize 3 digits with a signle model I have 30 outputs, each 10 corresponding to the probabilities of each digit.

The implementation is based on PyTorch library and consists of:
* Data preparation
  * Loading dataset and marking labels
  * Data Augmentation using random rotation
* Creation of train and test functions for the chosen approach
* Creation of CNN model with 3 convolutional layers. Training and testing the model
* Showcasing the prediction on examples and measuring time of prediction

Requirements:
    pip install numpy
    pip install torch
    pip install Pillow
    pip install matplotlib
