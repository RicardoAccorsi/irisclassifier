# Binary Classification with Perceptron

## Overview

This project focuses on performing binary classification using the Perceptron algorithm to separate targets in the Iris dataset. The Iris dataset is a well-known dataset in machine learning and contains samples of three different species of iris flowers: Setosa, Versicolor, and Virginica.

For this project, the task was simplified by considering only two classes: Setosa and Versicolor. The goal is to train a Perceptron model to distinguish between these two classes based on the features provided in the dataset.

## Dataset

The dataset used in this project is the Iris dataset, which is available in scikit-learn's datasets module (`load_iris`). This dataset contains 150 samples with four features each: sepal length, sepal width, petal length, and petal width. Each sample is labeled with the species of iris it belongs to.

## Task

The main task of this project is to perform binary classification to separate the Setosa and Versicolor species from the Iris dataset using the Perceptron algorithm. The Perceptron is a simple linear classifier capable of learning a decision boundary that separates two classes.

## Implementation

The project involves the following steps:

1. **Data Loading**: Load the Iris dataset using `load_iris` from scikit-learn.
2. **Data Preprocessing**: Select only the samples corresponding to the Setosa and Versicolor species for binary classification. Preprocess the data if necessary, such as scaling features or splitting into training and testing sets.
3. **Model Training**: Train a Perceptron model using the selected features and labels.
4. **Model Evaluation**: Evaluate the trained model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score.
5. **Visualization**: Visualize the decision boundary learned by the Perceptron on a scatter plot of the data points.

## Dependencies

- Python 3.x
- NumPy
- scikit-learn
