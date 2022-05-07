# Perceptron

## Introduction

A Perceptron is an algorithm for supervised learning of binary classifiers. It's a simplified model of a biological neuron, and it is a type of linear classifier, i.e., a classifier that makes its predictions based on a linear predictor function combining a set of weights with the feature vector. The perceptron algorithm was invented in 1958 at the Cornell Aeronautical Laboratory by Frank Rosenblatt. 

Perceptron is a single layer neural network and a multi-layer perceptron is called Neural Networks. Perceptron is a linear classifier (binary). 

The perceptron consists of 4 parts:
* Input values or One input layer
* Weights and Bias
* Net sum
* Activation Function

## File

"The Perceptron.ipynb" contains the description and code of Perceptron algorithm, then it's applied on *breast_cancer* dataset loaded from *sklearn.datasets*.

## Dataset

"Breast cancer wisconsin (diagnostic) dataset" is a classic and very easy binary classification dataset. It has 2 classes of target labels: 212(WDBC-Malignant),357(WDBC-Benign); the total sample size is 569; 30 Dimensionality, features are real, numeric and positive. Features:radius (mean of distances from center to points on the perimeter), texture (standard deviation of gray-scale values), perimeter, area, smoothness (local variation in radius lengths), compactness (perimeter^2 / area - 1.0), concavity (severity of concave portions of the contour), concave points (number of concave portions of the contour), symmetry, fractal dimension (“coastline approximation” - 1). Creators are Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian.

## Reference

Sharma, S. (2019, October 11). What the hell is Perceptron? Medium. Retrieved May 5, 2022, from https://towardsdatascience.com/what-the-hell-is-perceptron-626217814f53 

Wikimedia Foundation. (2022, April 17). Perceptron. Wikipedia. Retrieved May 5, 2022, from https://en.wikipedia.org/wiki/Perceptron 