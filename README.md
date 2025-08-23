# Fraudulent or Legitimate? – Credit Card Fraud Detection

This project was developed as part of a Data Science course assignment, focusing on training a supervised machine learning model - specifically, a **Random Forest classifier** - to detect fraudulent credit card transactions using a highly imbalanced dataset from Kaggle.

## Dataset
The dataset used in this project can be downloaded from Kaggle: [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

## Project Highlights

### 1. Handling Imbalanced Dataset
- The dataset had a severe class imbalance between fraudulent and legitimate transactions.  
- Explored multiple resampling techniques to improve model performance:
  - **SMOTE (Synthetic Minority Oversampling Technique)**  
  - **Undersampling**  
  - **Hybrid approaches**  
- Ensured the model could detect fraud without sacrificing accuracy on legitimate transactions.

### 2. Feature Selection
- Applied and compared multiple statistical feature selection techniques to identify the optimal subset of features:  
  - **SelectKBest**  
  - **SelectPercentile**  
  - **False Positive Rate filtering**  
  - **ANOVA F-value**  
  - **Mutual Information**  

### 3. Model Evaluation
- Performance was assessed using metrics suitable for imbalanced classification tasks:  
  - **Precision**  
  - **Recall**  
  - **F1-score**  
  - **PR AUC (Precision-Recall Area Under Curve)**  

## Goal
Build a **reliable and fair fraud detection model** that performs well on both the majority (legitimate) and minority (fraudulent) classes.


