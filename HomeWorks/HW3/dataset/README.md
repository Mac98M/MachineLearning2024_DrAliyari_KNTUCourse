## Credit Card Fraud Detection Dataset

### Overview

The Credit Card Fraud Detection dataset from Kaggle contains transactions made by credit cards in September 2013 by European cardholders. It is highly unbalanced, with 492 frauds out of 284,807 transactions. The dataset features 30 attributes: 28 anonymized numerical features obtained through PCA, along with 'Time' and 'Amount'. The 'Class' attribute is the response variable, with 1 indicating fraud and 0 indicating non-fraud.

### Imbalance in the Dataset

The dataset is highly imbalanced, with only 492 frauds out of 284,807 transactions, which is about 0.172% of all transactions. This imbalance poses a significant challenge for the development of effective fraud detection models, as the model must be able to accurately identify rare fraudulent transactions amidst a large number of legitimate transactions.

### Usage

This dataset is widely used for:

- **Benchmarking anomaly detection algorithms:** Given its imbalance, it is a good test case for how well different algorithms can detect anomalies (fraudulent transactions).
- **Evaluating classification models:** It allows the comparison of various machine learning models in terms of their ability to handle imbalanced data and accurately classify rare events.

### Applications in Mini Project 3

In this mini project, the Credit Card Fraud Detection dataset was used to:

1. **Evaluate the performance of Support Vector Machines (SVM) with different kernels (linear and polynomial).**
2. **Apply dimensionality reduction techniques (t-SNE, PCA, LDA) to visualize the dataset and improve the model's performance.**
3. **Implement autoencoder neural networks for data denoising and SMOTE (Synthetic Minority Over-sampling Technique) for addressing class imbalance.

### Data Source

The dataset is publicly available on Kaggle and can be accessed via the following link: [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

### Citation

If you use this dataset in your research, please cite the following paper:

```plaintext
Andrea Dal Pozzolo, Olivier Caelen, Reid A. Johnson and Gianluca Bontempi. 
Calibrating Probability with Undersampling for Unbalanced Classification. 
In Proceedings of the 2015 IEEE Symposium Series on Computational Intelligence (SSCI 2015), 2015
