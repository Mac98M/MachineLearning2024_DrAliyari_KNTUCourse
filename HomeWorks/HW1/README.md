# Mini Project 1: Training and Evaluating Machine Learning Classifiers

Welcome to the Mini Project 1 repository. This project focuses on the training and evaluation of various machine learning classifiers and regression models using synthetic and real-world datasets. The project involves three main tasks, each exploring different aspects of machine learning.

## Project Overview

### Task Descriptions

#### Question 1: Linear Classifier
- **Objective:** To train and evaluate a linear classifier on a synthetic dataset.
- **Details:**
  - Generated a synthetic dataset with 3 features and 4 classes using the `sklearn.datasets` module.
  - Implemented and evaluated a linear classifier with different hyperparameters.
  - Visualized decision boundaries and classification results.
- **Code Link:** [Q1](https://colab.research.google.com/drive/1sDNapu9NXL0X7_wT8Ne8L7IFOoae4-QB?usp=sharing)

#### Question 2: Multi-layer Perceptron (MLP) on CWRU Bearing Dataset
- **Objective:** To extend the dataset and perform feature extraction for training MLP models.
- **Details:**
  - Extended the CWRU Bearing dataset by adding more fault classes.
  - Performed feature extraction and data preparation.
  - Trained and evaluated MLP models with different architectures.
  - Implemented K-Fold and Stratified K-Fold cross-validation methods.
- **Code Link:** [Q2](https://colab.research.google.com/drive/1n2_XaebwkQXjIUKGk4crT_Kc2tnwLnAY?usp=sharing)

#### Question 3: Regression Analysis on Weather Dataset
- **Objective:** To perform regression analysis using various techniques.
- **Details:**
  - Analyzed the relationship between temperature and humidity in the Weather in Szeged dataset.
  - Applied techniques like Least Squares (LS), Regularized Least Squares (RLS), and Weighted Least Squares (WLS) to predict temperature.
  - Compared the performance of different regression models.
- **Code Link:** [Q3](https://colab.research.google.com/drive/15DaYmbCbfDgCKpLUjffQ4YwfdhYECHF9?usp=sharing)

## Dataset Information

### Generated Dataset for Classification
- **Overview:** A synthetic dataset generated using the `sklearn.datasets` module for binary and multi-class classification tasks.
- **Usage:** Used in Question 1 to train and evaluate a linear classifier.

### CWRU Bearing Dataset
- **Overview:** Contains vibration data collected from a motor with different fault conditions and speeds. Used for bearing fault diagnosis and condition monitoring.
- **Usage:** Used in Question 2 to train and evaluate MLP models.
- **Data Source:** [Case Western Reserve University Bearing Data Center](https://engineering.case.edu/bearingdatacenter)

### Weather Dataset
- **Overview:** Contains weather data collected over 10 years, providing attributes related to temperature, humidity, and other conditions. Used for regression tasks.
- **Usage:** Used in Question 3 for regression analysis.
- **Data Source:** [Weather Dataset on Kaggle](https://www.kaggle.com/datasets/budincsevity/szeged-weather)

