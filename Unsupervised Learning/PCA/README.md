# Principal Component Analysis

## Introduction

Principal component analysis (PCA) is the process of computing the principal components and using them to perform a change of basis on the data, sometimes using only the first few principal components and ignoring the rest. In data analysis, the first principal component of a set of *p* variables, presumed to be normally distributed, is the derived variable formed as a linear combination of the original variables that explains the most variance. The second principal component explains the most variance in what is left once the effect of the first component is removed, and we may proceed through *p* 
iterations until all the variance is explained.

PCA was invented in 1901 by Karl Pearson, as an analogue of the principal axis theorem in mechanics; it was later independently developed and named by Harold Hotelling in the 1930s.

## File

"Principal Component Analysis.ipynb" contains the description and code of PCA algorithm, then it's applied on *penguins* dataset loaded from *seaborn*.

## Dataset

"Palmer Archipelago (Antarctica) penguin dataset" from seaborn has 344 entries, 0 to 343, 7 columns: 
species:penguin species (Chinstrap, Adélie, or Gentoo)
culmen_length_mm: culmen length (mm)
culmen_depth_mm: culmen depth (mm)
flipper_length_mm: flipper length (mm)
body_mass_g: body mass (g)
island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)
sex: penguin sex

## Reference

Wikimedia Foundation. (2022, May 5). Principal component analysis. Wikipedia. Retrieved May 5, 2022, from https://en.wikipedia.org/wiki/Principal_component_analysis 