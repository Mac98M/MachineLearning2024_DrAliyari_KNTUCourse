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


### Methods and Techniques

- **Dimensionality Reduction:** Applied in MLP models to improve performance on the extended CWRU dataset.
- **Cross-Validation:** Implemented K-Fold and Stratified K-Fold cross-validation methods for model evaluation.
- **Ensemble Methods:** Compared decision tree classifiers with ensemble methods like Random Forest and AdaBoost.
- **Autoencoders and SMOTE:** Implemented for data denoising and addressing class imbalance, respectively.

## Links to Google Colab Notebooks
- **Implementation McCulloch-Pitts:** [Q1](https://colab.research.google.com/drive/1kArNn1D5TADjH7yIPWhrTBEHnEt18PnT?usp=sharing)
- **MLP:** [Q2](https://colab.research.google.com/drive/1nV2djffDYJF--97fBHS3DmZTIi7dWh7h?usp=sharing)
- **Decision Trees, Random Forest:** [Q3](https://colab.research.google.com/drive/18IklvkgDHrH45lYyN4chG9UFq2AQN8rX?usp=sharing)
- **Naive Bayes:** [Q4](https://colab.research.google.com/drive/198kllTQK4Q0mSq8fGQqtB7culZ11JsYl?usp=sharing)
