# K-Nearest-Neighbour (KNN) Implementation

__Overview__

This repository contains the implementation of the K-nearest neighbours (KNN) algorithm from scratch. The goal of this assignment was to implement the core functionality of KNN, including distance calculation and majority voting for predictions, without relying on external libraries for these specific tasks. The implementation was done in Python using Google Colab, a cloud-based Jupyter notebook environment.

__Dataset__

The dataset used for this assignment is a modified version of the Optical Recognition of Handwritten Digits Dataset from the UCI repository. It consists of pre-processed black-and-white images of the digits 5 and 6. Each row in the dataset represents an image, and each column represents a feature (the number of black pixels in a 4x4 patch). The dataset includes:

- train_inputs.csv: Input features for training.
- train_targets.csv: Corresponding class labels (5 or 6).

__Results__

The following results were obtained:

- Graph: A plot showing the average accuracy for k values ranging from 1 to 30.
- Best k Value: The optimal number of neighbours and its cross-validation accuracy.
- Test Accuracy: The accuracy of the KNN model on the test data using the best k value.
