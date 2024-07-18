# Dataset Information for Mini Project 2

This folder contains the datasets used for the various tasks in Mini Project 2: Comparative Analysis of Machine Learning Classifiers. Below are the details of the datasets utilized in this project.

## CWRU Bearing Dataset

### Overview
The CWRU Bearing dataset contains vibration data collected from a motor with different fault conditions and speeds. This dataset is widely used for bearing fault diagnosis and condition monitoring.

### Dataset Characteristics
- **Number of Instances:** Various files depending on the fault conditions.
- **Number of Features:** Multiple time-domain vibration signal measurements.
- **Fault Types:** The dataset includes normal operation and three types of faults.
- **Usage in Project:**
  - **Question 2:** The dataset was extended by adding more fault classes. Feature extraction and data preparation were performed to create a robust dataset for training and evaluating Multi-layer Perceptron (MLP) models.

### Data Source
The dataset can be accessed from the CWRU Bearing Data Center:
[Case Western Reserve University Bearing Data Center](https://engineering.case.edu/bearingdatacenter)

## Heart Disease Dataset

### Overview
The Heart Disease dataset is used to predict the presence of heart disease in patients. This dataset is commonly used in medical research for binary classification tasks.

### Dataset Characteristics
- **Number of Instances:** 303
- **Number of Features:** 14 attributes including age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, the slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, and thalassemia.
- **Response Variable:** Presence of heart disease (1) or absence (0).

### Usage in Project
- **Question 4:** The dataset was used to train a Gaussian Naive Bayes classifier. The model's performance was evaluated using cross-validation methods, and the differences between predicted and actual values were analyzed.

### Data Source
The dataset is publicly available on Kaggle and can be accessed via the following link:
[Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## Drug Classification Dataset

### Overview
The Drug Classification dataset contains information about drug prescriptions. This dataset is often used for classification tasks to determine the type of drug prescribed based on various patient attributes.

### Dataset Characteristics
- **Number of Instances:** Varies depending on the specific subset used.
- **Number of Features:** Attributes include age, sex, blood pressure levels, cholesterol levels, sodium to potassium ratio, and drug type.
- **Response Variable:** Type of drug prescribed (DrugA, DrugB, DrugC, DrugX, DrugY).

### Usage in Project
- **Question 3:** The dataset was used to train decision tree classifiers and evaluate their performance. Parameter tuning was applied, and the performance was compared with ensemble methods like Random Forest and AdaBoost.

### Data Source
The dataset can be accessed from Kaggle:
[Drug Classification Dataset on Kaggle](https://www.kaggle.com/datasets/pablomgomez21/drugs-a-b-c-x-y-for-decision-trees)
