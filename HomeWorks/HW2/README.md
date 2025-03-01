# Mini Project 2: Implementation and Comparison of MLP, Decision Trees, Random Forest, and Naive Bayes

This repository contains the implementation of various machine learning classifiers, including Multi-layer Perceptron (MLP), Random Forest, and Naive Bayes using Python. The project aims to provide a comparative analysis of these classifiers on different datasets. This project explores the implementation and evaluation of several machine learning classifiers. The goal is to compare their performance on specific datasets and understand their strengths and weaknesses.

## Project Overview

### Classifiers Implemented
- **Multi-layer Perceptron (MLP):** Implemented with varying architectures and activation functions.
- **Decision Tree and Random Forest:** Compared with individual classifiers to assess the improvement in performance.
- **Naive Bayes:** Applied to datasets assuming Gaussian distribution of features.

### Objectives
- Compare the performance of different classifiers on given datasets.
- Analyze the impact of various hyperparameters on classifier performance.
- Understand the strengths and weaknesses of each classifier.

### Project Tasks

#### Question 1: Multi-layer Perceptron (MLP)
1. **Activation Functions:** Comparison of sigmoid and ReLU activation functions in a two-class classification problem.
2. **Custom Activation Function:** Implement and evaluate a custom activation function (ELU).
3. **Neuron Design:** Design a simple neuron (McCulloch-Pitts) to classify regions inside a triangle.

#### Question 2: Multi-layer Perceptron (MLP) on CWRU Dataset
1. **CWRU Dataset Extension:** Extend the CWRU dataset by adding more fault classes.
2. **Feature Extraction and Preparation:** Perform feature extraction and data preparation for the extended dataset.
3. **MLP Training:** Train an MLP model on the prepared dataset, analyze accuracy, and plot loss and accuracy curves.
4. **Cross-Validation:** Implement K-Fold and Stratified K-Fold cross-validation methods.

#### Question 3: Decision Tree and Random Forests
1. **Dataset Selection:** Use a dataset related to drug classification or forest cover type.
2. **Decision Tree Training:** Train a decision tree classifier and evaluate its performance.
3. **Parameter Tuning:** Analyze the effect of hyperparameters on the decision tree's performance and apply pruning.
4. **Ensemble Methods:** Compare the decision tree with ensemble methods like Random Forest and AdaBoost.

#### Question 4: Naive Bayes
1. **Heart Disease Dataset:** Use the Heart Disease dataset to train a Gaussian Naive Bayes classifier.
2. **Cross-Validation:** Compare the performance using Micro and Macro average methods.
3. **Prediction Analysis:** Analyze the differences between the predicted and actual values.


