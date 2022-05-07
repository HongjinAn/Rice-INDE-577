# Decision and Regression Tree

## Introduction

### Decision Tree

A decision tree is a decision support tool that uses a tree-like model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.
Decision trees are commonly used in operations research, specifically in decision analysis, to help identify a strategy most likely to reach a goal, but are also a popular tool in machine learning.

#### Advantages and Disadvantages

1. Advantages of decision trees:

* Are simple to understand and interpret. People are able to understand decision tree models after a brief explanation.
* Have value even with little hard data. Important insights can be generated based on experts describing a situation (its alternatives, probabilities, and costs) and their preferences for outcomes.
* Help determine worst, best, and expected values for different scenarios.
* Use a white box model. If a given result is provided by a model.
* Can be combined with other decision techniques.
* The action of more than one decision-maker can be considered.

2. Disadvantages of decision trees:

* They are unstable, meaning that a small change in the data can lead to a large change in the structure of the optimal decision tree.
* They are often relatively inaccurate. Many other predictors perform better with similar data. This can be remedied by replacing a single decision tree with a random forest of decision trees, but a random forest is not as easy to interpret as a single decision tree.
* For data including categorical variables with different numbers of levels, information gain in decision trees is biased in favor of those attributes with more levels.
* Calculations can get very complex, particularly if many values are uncertain and/or if many outcomes are linked.

### Regression Tree
A regression tree is basically a decision tree that is used for the task of regression which can be used to predict continuous valued outputs instead of discrete outputs.

## File

"Decision & Regression Tree.ipynb" contains the description and code of Decision and Regression Tree algorithm. Decision Tree is applied on *iris* dataset loaded from *sklearn.datasets*. Regression Tree is applied on *wine*(Red Wine Quality) dataset loaded from kaggle.com.

## Dataset

The *iris* dataset is a classic and very easy multi-class classification dataset. It has 3 classes of target labels: Iris-Setosa, Iris-Versicolour, Iris-Virginica; the total sample size is 150 (50 per class); 4 Dimensionality, features are real, numeric and positive. Features:sepal length in cm, sepal width in cm, petal length in cm, petal width in cm. The famous Iris database, first used by Sir R.A. Fisher. The dataset is taken from Fisher’s paper.

The *wine*(Red Wine Quality) dataset from kaggle.com has 1359 entries, 0 to 1358, 12 columns: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, quality (score between 0 and 10). This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality


## Reference

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

Prasad, A. (2021, August 8). Regression trees: Decision tree for regression: Machine Learning. Medium. Retrieved May 7, 2022, from https://medium.com/analytics-vidhya/regression-trees-decision-tree-for-regression-machine-learning-e4d7525d8047 

Wikimedia Foundation. (2022, April 15). Decision tree. Wikipedia. Retrieved May 7, 2022, from https://en.wikipedia.org/wiki/Decision_tree 

