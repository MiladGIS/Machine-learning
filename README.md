# Classification Algorithms from Scratch

This practice contains the implementation of several classification algorithms from scratch, without using available libraries. The implemented algorithms are:

1. **K-Nearest Neighbors (KNN)**: KNN is a non-parametric, lazy learning algorithm. Its purpose is to use a database in which the data points are separated into several classes to predict the classification of a new sample point.

2. **Random Forest (RF)**: RF is a versatile machine learning method capable of performing both regression and classification tasks. It is a kind of ensemble learning method, where a few weak models combine to form a powerful model.

3. **AdaBoost**: AdaBoost (Adaptive Boosting) is a powerful classifier that works well on both basic and more complex recognition problems. AdaBoost works by creating a highly accurate classifier by combining many relatively weak and inaccurate classifiers.

4. **ID3 (Iterative Dichotomiser 3)**: ID3 algorithm creates a multiway tree, finding for each node (i.e. in a greedy manner) the categorical feature that will yield the largest information gain for categorical targets.

5. **Naive Bayes**: Naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong (naïve) independence assumptions between the features.

## Data classification
This folder contains:
* Mushroom dataset
* Breast cancer dataset
* Cars dataset
* Ecoli dataset
* Letter recognition dataset

Each dataset requires preproccesing and modification to be ready for classification. The .ipynb file repsresents performance of each algorithm on the datasets.

![image](https://github.com/MiladGIS/Machine-learning/assets/96174234/b01a56cf-3bf3-493d-bb9d-b93f1fd4f92e)


## Image classification
Keyframes, features, annotations of two concepts (building and explosion_fire) of 6 videos from TRECVID 2005 are stored in .rar file that needs to be extracted. Readme defines more about the dataset in hand.
On this dataset, KNN and Naive Bayes algorithms were developed from scratch, and the SVM algorithm from scikit-learn was used to compare the results. The PCA method was applied for dimensionality reduction of the dataset. The results of these practices are shown in .ipynb file.

![image](https://github.com/MiladGIS/Machine-learning/assets/96174234/ef0e717e-3fc3-4e53-a54c-8455a6b7626e)
