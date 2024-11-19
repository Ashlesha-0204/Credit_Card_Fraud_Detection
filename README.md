# Credit_Card_Fraud_Detection
Build a machine learning model to identify fraudulent credit card transactions. 

## Overview
This project involves building a machine learning model to identify fraudulent credit card transactions. The dataset contains transactions from European cardholders, with a small percentage of fraudulent transactions. The goal is to predict whether a given transaction is fraudulent or genuine based on the transaction's features.

### Key Objectives:
- **Handle Class Imbalance**: The dataset is highly imbalanced, with fraudulent transactions representing only 0.172% of the total transactions. Techniques like SMOTE (Synthetic Minority Over-sampling Technique) are used to address this.
- **Preprocessing & Normalization**: The data is normalized to ensure all features contribute equally to the model.
- **Model Building & Evaluation**: The project involves building two classification models—**Logistic Regression** and **Random Forest Classifier**—and evaluating them using various metrics like Precision, Recall, F1-Score, AUC, and ROC Curve.


### Key Techniques & Algorithms Used:
1. **Logistic Regression**: A binary classification algorithm used for predicting whether a transaction is fraudulent or not.
2. **Random Forest Classifier**: An ensemble classifier that builds multiple decision trees and aggregates their predictions.
3. **SMOTE**: Used to balance the classes by oversampling the minority class (fraudulent transactions).
4. **StandardScaler**: Normalizes the dataset to bring all features to a common scale.
5. **GridSearchCV**: Hyperparameter tuning used to find the optimal hyperparameters for the Logistic Regression model.
6. **Precision-Recall Curve & ROC Curve**: Performance evaluation metrics, especially important for imbalanced datasets.

### Dependencies:
-  pandas
-  numpy
-  matplotlib
-  seaborn
-  scikit-learn
