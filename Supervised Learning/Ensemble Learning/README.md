# Ensemble Learning

## Introduction

In statistics and machine learning, ensemble methods use multiple learning algorithms to obtain better predictive performance than could be obtained from any of the constituent learning algorithms alone. Unlike a statistical ensemble in statistical mechanics, which is usually infinite, a machine learning ensemble consists of only a concrete finite set of alternative models, but typically allows for much more flexible structure to exist among those alternatives.

## File

"Ensemble Methods (Bagging & Random Forests).ipynb" contains the description and code of Ensemble Methods algorithm, then it's applied on *penguins* dataset loaded from *seaborn*.

"Boosting.ipynb" contains the description and code of Ensemble Boosting algorithm. AdaBoost applied on *penguins* dataset loaded from *seaborn*. Gradient Boosting is applied on *wine*(Red Wine Quality) dataset loaded from kaggle.com and random generated numberical data..

## Dataset

"Palmer Archipelago (Antarctica) penguin dataset" from seaborn has 344 entries, 0 to 343, 7 columns: 
species:penguin species (Chinstrap, Adélie, or Gentoo)
culmen_length_mm: culmen length (mm)
culmen_depth_mm: culmen depth (mm)
flipper_length_mm: flipper length (mm)
body_mass_g: body mass (g)
island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)
sex: penguin sex

The *wine*(Red Wine Quality) dataset from kaggle.com has 1359 entries, 0 to 1358, 12 columns: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, quality (score between 0 and 10). This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality

## Reference

P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

Wikimedia Foundation. (2022, January 22). Ensemble learning. Wikipedia. Retrieved May 7, 2022, from https://en.wikipedia.org/wiki/Ensemble_learning 

