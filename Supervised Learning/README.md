# Supervised Learning

---

## Introduction
Supervised learning (SL) is the machine learning task of learning a function that maps an input to an output based on example input-output pairs. It infers a function from labeled training data consisting of a set of training examples. In supervised learning, each example is a pair consisting of an input object (typically a vector) and a desired output value (also called the supervisory signal). A supervised learning algorithm analyzes the training data and produces an inferred function, which can be used for mapping new examples.

Supervised learning is a process of providing input data as well as correct output data to the machine learning model. The aim of a supervised learning algorithm is to find a mapping function to map the input variable(x) with the output variable(y). In the real-world, supervised learning can be used for Risk Assessment, Image classification, Fraud Detection, spam filtering, etc.

![The working of Supervised Learning](https://github.com/HongjinAn/Rice-INDE-577/blob/main/Supervised%20Learning/supervised-machine-learning.png)

## Types
Supervised learning can be separated into two types of problems when data mining—classification and regression:

* **Classification** uses an algorithm to accurately assign test data into specific categories. It recognizes specific entities within the dataset and attempts to draw some conclusions on how those entities should be labeled or defined. Common classification algorithms are linear classifiers, support vector machines (SVM), decision trees, k-nearest neighbor, and random forest, which are described in more detail below.
* **Regression** is used to understand the relationship between dependent and independent variables. It is commonly used to make projections, such as for sales revenue for a given business. Linear regression, logistical regression, and polynomial regression are popular regression algorithms.

## Steps
1.Determine the type of training examples.
2.Gather a training set. 
3.Determine the input feature representation of the learned function. The accuracy of the learned function depends strongly on how the input object is represented.
4.Determine the structure of the learned function and corresponding learning algorithm.
5.Complete the design. Run the learning algorithm on the gathered training set. 
6.Evaluate the accuracy of the learned function. After parameter adjustment and learning, the performance of the resulting function should be measured on a test set that is separate from the training set.

---

## Unsupervised vs. Supervised Learning
Unlike unsupervised learning algorithms, supervised learning algorithms use labeled data. From that data, it either predicts future outcomes or assigns data to specific categories based on the regression or classification problem that it is trying to solve. While supervised learning algorithms tend to be more accurate than unsupervised learning models, they require upfront human intervention to label the data appropriately. However, these labelled datasets allow supervised learning algorithms to avoid computational complexity as they don’t need a large training set to produce intended outcomes. Common regression and classification techniques are linear and logistic regression, naïve bayes, KNN algorithm, and random forest.

---

## Algorithm

* Perceptron
* Linear Regression
* Gradient Descent
* Logistic Regression
* Neural Network
* K-Nearest Neighbors
* Decision & Regression Trees
* Ensemble Learning

---

## Challenges
Although supervised learning can offer businesses advantages, such as deep data insights and improved automation, there are some challenges when building sustainable supervised learning models. The following are some of these challenges:

* Supervised learning models can require certain levels of expertise to structure accurately.
* Training supervised learning models can be very time intensive.
* Datasets can have a higher likelihood of human error, resulting in algorithms learning incorrectly.
* Unlike unsupervised learning models, supervised learning cannot cluster or classify data on its own.

---

## Reference
IBM Cloud Education. (n.d.). What is supervised learning? IBM. Retrieved May 5, 2022, from https://www.ibm.com/cloud/learn/supervised-learning 

Supervised machine learning - javatpoint. www.javatpoint.com. (n.d.). Retrieved May 5, 2022, from https://www.javatpoint.com/supervised-machine-learning 

Wikimedia Foundation. (2022, February 24). Supervised learning. Wikipedia. Retrieved May 5, 2022, from https://en.wikipedia.org/wiki/Supervised_learning 
