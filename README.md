# Machine-Learning-binary-classification-and-Multilevel-Classification
: Binary Classification 
For this problem, we will use a subset of the Wisconsin Breast Cancer dataset

Multilevel Classification:
created a default One-vs-Rest Classifier.Used the data reduced_mnist.csv.Splited the data into 70% training data and 30% test data. Fit a One-vs-Rest Classifier (which uses Logistic regression classifier with alpha=1) on training data, and report accuracy, precision, recall on testing data.Choosed the best value of alpha from the set a={0.1, 1, 3, 10, 33, 100, 333, 1000, 3333, 10000, 33333} by observing average training and validation performance P.Used the best alpha and all training data to build the final model and then evaluate the prediction performance on test data.

#Discuss if there is any sign of underfitting or overfitting with appropriate reasoning
