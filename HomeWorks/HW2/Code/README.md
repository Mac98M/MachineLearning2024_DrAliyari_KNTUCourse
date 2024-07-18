# Mini Project 2: Implementation and Comparison of MLP, Decision Trees, Random Forest, and Naive Bayes

This mini-project explores the implementation and evaluation of several machine learning classifiers. The goal is to compare their performance on specific datasets and understand their strengths and weaknesses. The project involves:

## Project Overview

### Classifiers Implemented
- **Multi-layer Perceptron (MLP):**
  - Implemented with varying architectures and activation functions (sigmoid and ReLU).
  - Custom activation function (ELU) implementation and evaluation.
  - Designed a simple neuron (McCulloch-Pitts) to classify regions inside a triangle.

- **Random Forest:**
  - Trained on selected datasets related to drug classification or forest cover type.
  - Analyzed the effect of hyperparameters on performance and applied pruning.
  - Compared with ensemble methods like Random Forest and AdaBoost.

- **Naive Bayes:**
  - Applied to the Heart Disease dataset assuming Gaussian distribution of features.
  - Compared performance using Micro and Macro average methods.
  - Analyzed the differences between predicted and actual values.

### Datasets Used

#### CWRU Bearing Dataset
- **Overview:** Contains vibration data collected from a motor with different fault conditions and speeds. Used in Question 2.
- **Details:**
  - Extended by adding more fault classes.
  - Performed feature extraction and data preparation.
  - Used to train and evaluate MLP models.

#### Heart Disease Dataset
- **Overview:** Contains data related to heart disease diagnosis. Used in Question 4.
- **Details:**
  - Used to train a Gaussian Naive Bayes classifier.
  - Evaluated using cross-validation and analyzed prediction results.

#### Drug Classification or Forest Cover Type Dataset
- **Overview:** Used in Question 3.
- **Details:**
  - Trained decision tree classifiers and evaluated performance.
  - Applied parameter tuning and compared with ensemble methods.

### Methods and Techniques

- **Dimensionality Reduction:** Applied in MLP models to improve performance on the extended CWRU dataset.
- **Cross-Validation:** Implemented K-Fold and Stratified K-Fold cross-validation methods for model evaluation.
- **Ensemble Methods:** Compared decision tree classifiers with ensemble methods like Random Forest and AdaBoost.
- **Autoencoders and SMOTE:** Implemented for data denoising and addressing class imbalance, respectively.

## Links to Google Colab Notebooks

- **Question 1:** [Q1](https://colab.research.google.com/drive/1kArNn1D5TADjH7yIPWhrTBEHnEt18PnT?usp=sharing)
- **Question 2:** [Q2](https://colab.research.google.com/drive/1nV2djffDYJF--97fBHS3DmZTIi7dWh7h?usp=sharing)
- **Question 3:** [Q3](https://colab.research.google.com/drive/18IklvkgDHrH45lYyN4chG9UFq2AQN8rX?usp=sharing)
- **Question 4:** [Q4](https://colab.research.google.com/drive/198kllTQK4Q0mSq8fGQqtB7culZ11JsYl?usp=sharing)
