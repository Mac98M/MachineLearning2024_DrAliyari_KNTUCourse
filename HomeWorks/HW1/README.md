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

## CWRU Bearing Dataset

### Overview
The CWRU Bearing dataset contains vibration data collected from a motor with different fault conditions and speeds. This dataset is widely used for bearing fault diagnosis and condition monitoring.

### Dataset Characteristics
- **Number of Instances:** Various files depending on the fault conditions.
- **Number of Features:** Multiple time-domain vibration signal measurements.
- **Fault Types:** The dataset includes normal operation and different fault conditions.

### Usage in Project

#### Question 2
- **Objective:** To extend the dataset and perform feature extraction.
- **Details:**
  - Extended the CWRU dataset by adding more fault classes.
  - Extracted features and prepared the dataset for training MLP models.
  - Trained and evaluated MLP models with different architectures.
  - Implemented K-Fold and Stratified K-Fold cross-validation.
  - **Code Link:** [Q2](https://colab.research.google.com/drive/1n2_XaebwkQXjIUKGk4crT_Kc2tnwLnAY?usp=sharing)

### Data Source
The dataset can be accessed from the CWRU Bearing Data Center:
[Case Western Reserve University Bearing Data Center](https://engineering.case.edu/bearingdatacenter)

## Weather Dataset

### Overview
The Weather in Szeged dataset contains weather data collected over a period of 10 years, providing a comprehensive set of attributes related to temperature, humidity, and other weather conditions. This dataset is often used for regression tasks.

### Dataset Characteristics
- **Number of Instances:** Varies depending on the specific subset used.
- **Number of Features:** Attributes include temperature, humidity, wind speed, and more.

### Usage in Project

#### Question 3
- **Objective:** To perform regression analysis.
- **Details:**
  - Analyzed the relationship between temperature and humidity.
  - Used techniques like LS, RLS, and WLS to predict temperature.
  - Compared the performance of different regression models.
  - **Code Link:** [Q3](https://colab.research.google.com/drive/15DaYmbCbfDgCKpLUjffQ4YwfdhYECHF9?usp=sharing)

### Data Source
The dataset can be accessed from Kaggle:
[Weather Dataset on Kaggle](https://www.kaggle.com/datasets/budincsevity/szeged-weather)

---
