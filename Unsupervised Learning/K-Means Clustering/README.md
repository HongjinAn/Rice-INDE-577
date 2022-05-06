# K-Means Clustering

## Introduction

K-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. 

The term "k-means" was first used by James MacQueen in 1967, though the idea goes back to Hugo Steinhaus in 1956. The standard algorithm was first proposed by Stuart Lloyd of Bell Labs in 1957 as a technique for pulse-code modulation, although it was not published as a journal article until 1982. In 1965, Edward W. Forgy published essentially the same method, which is why it is sometimes referred to as the Lloyd–Forgy algorithm.

K-means clustering is a common example of an exclusive clustering method where data points are assigned into K groups, where K represents the number of clusters based on the distance from each group’s centroid. The data points closest to a given centroid will be clustered under the same category. A larger K value will be indicative of smaller groupings with more granularity whereas a smaller K value will have larger groupings and less granularity. K-means clustering is commonly used in market segmentation, document clustering, image segmentation, and image compression.

## File

"K-Means Clustering.ipynb" contains the description and code of k-means algorithm, then it's applied on *breast_cancer* dataset loaded from *sklearn.datasets*.

## Dataset

"Breast cancer wisconsin (diagnostic) dataset" is a classic and very easy binary classification dataset. It has 2 classes of target labels: 212(WDBC-Malignant),357(WDBC-Benign); the total sample size is 569; 30 Dimensionality, features are real, numeric and positive. Features:radius (mean of distances from center to points on the perimeter), texture (standard deviation of gray-scale values), perimeter, area, smoothness (local variation in radius lengths), compactness (perimeter^2 / area - 1.0), concavity (severity of concave portions of the contour), concave points (number of concave portions of the contour), symmetry, fractal dimension (“coastline approximation” - 1). Creators are Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian.

## Reference

IBM Cloud Education. (n.d.). What is unsupervised learning? IBM. Retrieved May 5, 2022, from https://www.ibm.com/cloud/learn/unsupervised-learning 

Sklearn.datasets.load_breast_cancer. scikit. (n.d.). Retrieved May 5, 2022, from https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html 

Wikimedia Foundation. (2022, April 28). K-means clustering. Wikipedia. Retrieved May 5, 2022, from https://en.wikipedia.org/wiki/K-means_clustering 