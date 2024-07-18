# Mini Project 1

This folder contains the datasets used for the various tasks in Mini Project 1: Training and Evaluating Machine Learning Classifiers. Below are the details of the datasets utilized in this project.

## Generated Dataset for Classification

### Overview
For the purposes of this mini project, we generated a synthetic dataset using the `sklearn.datasets` module. This dataset was designed to facilitate the training and evaluation of different classifiers, particularly focusing on binary and multi-class classification tasks.

### Dataset Characteristics
- **Number of Instances:** 1000 samples
- **Number of Features:** Various features generated to test different classification models
- **Classes:** Dataset includes instances from multiple classes, used to evaluate the performance of classifiers in both binary and multi-class settings.

### Usage in Project

#### Question 1
- **Objective:** To train and evaluate a linear classifier.
- **Details:**
  - Generated a dataset with 3 features and 4 classes.
  - Evaluated and trained a linear classifier using different hyperparameters.
  - Visualized decision boundaries and classification results.
  - **Code Link:** [Q1](https://colab.research.google.com/drive/1wyNMAbldTOmtLREfD8gbtbix-D96BQAJ?usp=sharing)
- **Generation Command:**
  ```python
  from sklearn.datasets import make_classification
  X, y = make_classification(n_samples=1000, n_features=3, n_classes=4, random_state=42)
  ```



