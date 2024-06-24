This mini-project explores the impact of various dimensionality reduction techniques on the performance of machine learning models, specifically Support Vector Machines (SVM). The project involves:

Dimensionality Reduction: Implementing and comparing t-SNE, PCA, and LDA to reduce the dimensionality of the dataset while retaining critical information.
SVM Model Implementation: Evaluating SVM with linear and polynomial kernels. The polynomial SVM is implemented from scratch and compared against the scikit-learn implementation for polynomial degrees from 1 to 10.
Autoencoders and SMOTE: Implementing autoencoders for data denoising and using SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance. These methods are applied to improve the model's performance on the highly imbalanced credit card fraud detection dataset.
The project demonstrates the significant improvements in model accuracy and robustness through effective preprocessing and balancing techniques.

Dataset Information
The Credit Card Fraud Detection dataset from Kaggle consists of transactions made by European cardholders in September 2013. It includes 284,807 transactions, with only 492 being fraudulent, making it highly imbalanced. The dataset has 30 features, including 28 anonymized numerical features obtained through PCA, and 'Time' and 'Amount'. The 'Class' attribute indicates fraud (1) or non-fraud (0). This dataset is used to benchmark anomaly detection algorithms and was utilized in question 3 of this project to apply dimensionality reduction techniques and SVM models with various kernels.
