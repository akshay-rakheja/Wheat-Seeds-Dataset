# Wheat seeds Dataset

This small dataset is the UCI Seeds Data set (https://archive.ics.uci.edu/ml/datasets/seeds). The examined group comprised kernels belonging
to three different varieties of wheat: Kama, Rosa and Canadian. These are the labels. There are 70 elements for each variety of wheat, randomly selected
for the experiment.

### Goals
1. Classify the data using three tree-based classifiers: Decision Trees, Random Forests and Gradient Tree Boosting. Tune the hyper-parameters of the classifier
using 10-fold cross validation and sklearn functions. Evaluate the best value for the number of trees and maximum depth of trees.
2. Across both datasets, compare and contrast the performance of the three approaches and point out any interesting patterns.
3. Classify the data using the Naive Bayes Classifier
4. Tune the hyper-parameters of the classifier using 10-fold cross valida-tion and sklearn functions.Evaluate the best value for the var smoothing among the values {1e-10, 1e-
9, 1e-5, 1e-3, 1e-1}
