# Image-Classification-Model-on-CIFAR-10-dataset

This repository contains code for classifying images from the CIFAR-10 dataset using machine learning and deep learning techniques. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class.
Given an image, can we predict the correct class of this image?

The images are very small (32x32) and by visualizing them you will notice how difficult it is to distinguish them even for a human.

In this notebook we are going to build a CNN model that can classify images of various objects. We have 10 class of images:

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

## Project Overview
The project involves:

1. Loading and preprocessing the CIFAR-10 dataset
2. Building and training a convolutional neural network (CNN) model
3. Evaluating the model's performance
4. Visualizing the results

## Usage
1. Open the Jupyter Notebook:

        jupyter notebook image_classification_CIFAR_10.ipynb
2. Follow the steps in the notebook to:

  1. Load and preprocess the data
  2. Build and compile the CNN model
  3. Train the model on the training data
  4. Evaluate the model on the test data
  5. Visualize the training process and results

## Results
The CNN model was trained on the CIFAR-10 dataset and achieved the following results:

  1. Training Accuracy: 87..49%
  2. Validation Accuracy: 97.04%
  3. Test Accuracy: 86.16%

     
These results indicate that the model is able to classify CIFAR-10 images with a reasonable level of accuracy. Further improvements can be made by experimenting with different architectures, hyperparameters, and data augmentation techniques.
