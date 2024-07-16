# Mini Project 3: Support Vector Machines (SVM) and Dimensionality Reduction

This mini-project explores the impact of various dimensionality reduction techniques on the performance of machine learning models, specifically Support Vector Machines (SVM). The project involves:

## Project Overview

### Dimensionality Reduction
- **Implementing and comparing t-SNE, PCA, and LDA:** These techniques are used to reduce the dimensionality of the dataset while retaining critical information.

### SVM Model Implementation
- **Evaluating SVM with linear and polynomial kernels:** We implemented SVM with both linear and polynomial kernels, comparing a custom-built polynomial SVM with the scikit-learn library implementation for polynomial degrees ranging from 1 to 10.

### Autoencoders and SMOTE
- **Data Denoising and Class Imbalance:** We explored using autoencoders for denoising data and SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance. These methods are applied to improve the model's performance on the highly imbalanced credit card fraud detection dataset.

The project demonstrates the significant improvements in model accuracy and robustness through effective preprocessing and balancing techniques.

## Detailed Explanation

### Question 1: SVM on the Iris Dataset

The objective of this question is to apply the SVM algorithm to the famous Iris dataset and analyze its performance using different kernels and dimensionality reduction techniques.

#### Steps:
1. **Data Analysis:**
   - Extract statistical information such as mean, variance, and correlations.
   - Visualize the dataset using t-SNE, PCA, and LDA to understand the distribution and feasibility of dimensionality reduction.

2. **SVM Implementation:**
   - Use SVM with linear and polynomial kernels from the `scikit-learn` library.
   - Compare the performance using appropriate metrics like accuracy, precision, and recall.

3. **Visualization:**
   - Visualize decision boundaries using different kernels.
   - Create a GIF to visualize the decision boundaries for polynomial degrees from 1 to 10.

4. **Custom SVM Implementation:**
   - Implement the SVM algorithm from scratch without using `scikit-learn`.
   - Define a class for SVM that includes `fit`, `predict`, and `polynomial_kernel` methods.
   - Compare the custom implementation with the `scikit-learn` implementation.

5. **Performance Evaluation:**
   - Analyze the performance using a confusion matrix.
   - Evaluate the classifier using metrics like accuracy, precision, and recall.

### Question 2: GenSVM - A Generalized Multiclass Support Vector Machine

The objective of this question is to understand and implement the GenSVM algorithm and compare its performance with traditional SVMs.

#### Steps:
1. **Study and Summarize:**
   - Read the GenSVM paper.
   - Summarize the problem statement, methodology, and innovative aspects of the algorithm.

2. **Implementation:**
   - Implement the GenSVM algorithm using appropriate libraries.
   - Use the Iris dataset for testing the implementation.

3. **Performance Evaluation:**
   - Compare the results of GenSVM with traditional SVMs.
   - Use appropriate metrics to evaluate the performance.

### Question 3: Credit Card Fraud Detection Using Autoencoder Neural Network

The objective of this question is to apply autoencoder neural networks for detecting credit card fraud, addressing challenges such as class imbalance and data noise.

#### Steps:
1. **Challenge Analysis:**
   - Identify major challenges in developing credit card fraud detection models and the methods used to address these challenges.

2. **Autoencoder Implementation:**
   - Implement an autoencoder neural network to detect fraud.

3. **Model Training:**
   - Train the autoencoder using the credit card fraud dataset, ensuring to prevent overfitting and adjust the model based on validation errors.

4. **Performance Evaluation:**
   - Evaluate the model using metrics like accuracy, precision, recall, and F1-Score.
   - Create confusion matrices and performance curves.

5. **Model Adjustment:**
   - Adjust the model to improve performance based on validation errors.
   - Use techniques like oversampling to handle class imbalance.

