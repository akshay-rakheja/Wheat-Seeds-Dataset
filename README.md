# Tree-Based-Classifiers

Dataset 1 - Wheat Seeds

This small dataset is the UCI Seeds Data set (https://archive.ics.uci.edu/ml/datasets/seeds). The examined group comprised kernels belonging
to three different varieties of wheat: Kama, Rosa and Canadian. These are the labels. There are 70 elements for each variety of wheat, randomly selected
for the experiment.

Dataset 2 - Covid-19 Outcomes in Ontario

Dataset 2 is about the confirmed COVID-19 cases in Ontario. The original data comes from the following
confirmed positive cases of COVID19 in Ontario" at: https://data.ontario.ca/dataset/confirmed-positive-cases-of-covid-19-in-ontario
I will be using the features: age group, gender, case acquisition info, city, outbreak, latitude, and longitude. 

### Goals
1. Classify the data using three tree-based classifiers: Decision Trees, Random Forests and Gradient Tree Boosting. Tune the hyper-parameters of the classifier
using 10-fold cross validation and sklearn functions. Evaluate the best value for the number of trees and maximum depth of trees.
2. Across both datasets, compare and contrast the performance of the three approaches and point out any interesting patterns.
