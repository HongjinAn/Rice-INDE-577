# K-Nearest Neighbors

# Scikit-Learn: Desicion Boundary & The Confusion Matrix

## Introduction

### K-Nearest Neighbors
In statistics, the k-nearest neighbors algorithm (k-NN) is a non-parametric supervised learning method first developed by Evelyn Fix and Joseph Hodges in 1951, and later expanded by Thomas Cover. It is used for classification and regression. In both cases, the input consists of the k closest training examples in a data set. The output depends on whether k-NN is used for classification or regression:

In k-NN classification, the output is a class membership. An object is classified by a plurality vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small). If k = 1, then the object is simply assigned to the class of that single nearest neighbor.
In k-NN regression, the output is the property value for the object. This value is the average of the values of k nearest neighbors.

### Desicion Boundary
A decision boundary is a line (in the case of two features), where all (or most) samples of one class are on one side of that line, and all samples of the other class are on the opposite side of the line. The line separates one class from the other. If you have more than two features, the decision boundary is not a line, but a (hyper)-plane in the dimension of your feature space.

### The Confusion Matrix
In the field of machine learning and specifically the problem of statistical classification, a confusion matrix, also known as an error matrix, is a specific table layout that allows visualization of the performance of an algorithm, typically a supervised learning one (in unsupervised learning it is usually called a matching matrix). Each row of the matrix represents the instances in an actual class while each column represents the instances in a predicted class, or vice versa – both variants are found in the literature. The name stems from the fact that it makes it easy to see whether the system is confusing two classes (i.e. commonly mislabeling one as another).

## File

"K-Nearest Neighbors.ipynb" contains the description and code of K-Nearest Neighbors algorithm, then it's applied on *penguins* dataset loaded from *sklearn.datasets* and *songs* (Spotify 2010 - 2019 Top 100) dataset from kaggle.com.

"Scikit-Learn Library(KNN, Decision Boundary, Confusion Matrix).ipynb" contains the description and code of KNN, Decision Boundary, Confusion Matrix algorithm, and it's applied on *penguins* dataset loaded from *sklearn.datasets*

## Dataset

"Palmer Archipelago (Antarctica) penguin dataset" from seaborn has 344 entries, 0 to 343, 7 columns: 
species:penguin species (Chinstrap, Adélie, or Gentoo)
culmen_length_mm: culmen length (mm)
culmen_depth_mm: culmen depth (mm)
flipper_length_mm: flipper length (mm)
body_mass_g: body mass (g)
island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)
sex: penguin sex

"Spotify 2010 - 2019 Top 100.csv" from Kaggle.com has 1003 entreis, 0 to 1002, 16 columns:
title: Song's Title
artist: Song's artist
top genre: Genre of song
year released
added: Day song was added to Spotify's Top Hits playlist
bpm: Beats Per Minute - The tempo of the song
nrgy: Energy - How energetic the song is
dnce: Danceability - How easy it is to dance to the song
dB: Decibel - How loud the song is
live: How likely the song is a live recording
val: How positive the mood of the song is
dur: Duration of the song
acous
spch
pop
top year: Year the song was a top hit
artist type: Tells if artist is solo, duo, trio, or a band

## Reference

Badgujar, A. (2022, April 27). Spotify Top 100 songs of 2010-2019. Kaggle. Retrieved May 7, 2022, from https://www.kaggle.com/datasets/amey22/spotify-top-100-songs-of-2010-2019 

Decision boundaries. Decision Boundaries – Machine Learning. (n.d.). Retrieved May 7, 2022, from https://huppenkothen.org/machine-learning-tutorial/05-DecisionBoundaries/index.html 

Wikimedia Foundation. (2021, December 3). Confusion matrix. Wikipedia. Retrieved May 7, 2022, from https://en.wikipedia.org/wiki/Confusion_matrix 

Wikimedia Foundation. (2022, March 15). K-nearest neighbors algorithm. Wikipedia. Retrieved May 7, 2022, from https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm 
