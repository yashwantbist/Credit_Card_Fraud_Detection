# Credit_Card_Fraud_Detection
This project demonstrates how to detect fraudulent credit card transactions using **Decision Tree** and **Support Vector Machine (SVM)** classifiers from the Scikit-Learn library. It focuses on handling imbalanced data and optimizing model performance using feature selection and ROC-AUC evaluation.

## Project Objectives

- Perform basic data preprocessing and scaling
- Handle imbalanced dataset using class weighting
- Train and evaluate models using Decision Tree and Linear SVM
- Select top correlated features for performance optimization
- Evaluate models using the ROC-AUC score


##  Dataset

We use the **Credit Card Fraud Detection dataset** from Kaggle:  
🔗 [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

- The dataset contains 284,807 transactions, out of which only 492 are frauds (~0.172%).
- Features V1–V28 are results of PCA transformation for confidentiality.
- The target variable is `Class` (1 = fraud, 0 = legitimate).

##  Technologies Used

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- numpy

---

## Data Preprocessing

- Removed the `Time` feature.
- Applied `StandardScaler` and `normalize()` for better model convergence.
- Performed **class weighting** to balance the imbalanced dataset during training.

---

## Machine Learning Models
### 1.Decision Tree Classifier
### 2. Linear Support Vectoer Machine
