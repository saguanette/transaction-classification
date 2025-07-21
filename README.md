# Fraudulent or Legitimate? 
This project was developed as part of a Data Science course assignment, focusing on training a supervised machine learning model - specifically, a **Random Forest** classifier - to detect fraudulent credit card transactions using a highly imbalanced dataset from Kaggle.

- Imbalanced Dataset Handling:
The original dataset had a severe class imbalance. To address this, multiple resampling techniques (such as SMOTE, undersampling, and hybrid approaches) were explored to improve the model's ability to detect fraud without sacrificing accuracy on legitimate transactions.

- Feature Selection: Multiple statistical feature selection techniques were applied and compared - including SelectKBest, SelectPercentile, False Positive Rate filtering, ANOVA F-value, and mutual information to identify the optimal subset of features.

- Model Evaluation: Model performance was assessed using metrics suitable for imbalanced classification tasks, including Precision, Recall, F1-score, and PR AUC.

- Goal:
The aim was to build a reliable and fair fraud detection model that performs well on both majority and minority classes.

- The dataset used for this project can be downloaded from [here](https://www.kaggle.com/datasets/kartik2112/fraud-detection)
