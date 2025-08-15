# 💳 Credit Card Fraud Detection

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle-orange)

A machine learning project to detect fraudulent credit card transactions using advanced classification algorithms and data preprocessing techniques.  
The goal is to build a robust, scalable model that can accurately identify fraudulent activity while minimizing false positives.

---

## 📦 Dataset

**Source**: [Credit Card Fraud Detection – Kaggle (by Kartik2112)](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

**Description**:  
The dataset contains anonymized credit card transaction records, with features transformed for confidentiality.  
It is highly imbalanced, with fraudulent transactions making up a small fraction of the total.

**Key Columns**:
- `TransactionID` – Unique identifier for each transaction  
- `TransactionDT` – Time delta from a reference point  
- `TransactionAmt` – Transaction amount  
- `ProductCD` – Product code  
- `cardX` – Card details (anonymized)  
- `addrX` – Address details (anonymized)  
- `distX` – Distance metrics  
- `P_emaildomain` / `R_emaildomain` – Email domains  
- `isFraud` – Target variable (1 = Fraud, 0 = Legitimate)  

---

## 🎯 Objectives

- Handle **class imbalance** using resampling techniques (SMOTE, undersampling, etc.)  
- Perform **feature engineering** and preprocessing  
- Train multiple machine learning models  
- Evaluate models using metrics beyond accuracy (Precision, Recall, F1, ROC-AUC)  
- Optimize hyperparameters for best performance  
- Provide a reproducible pipeline for fraud detection tasks  

---

## 🧰 Tech Stack

| Category         | Tools Used                          |
|------------------|-------------------------------------|
| Language         | Python 3.x                          |
| Data Handling    | Pandas, NumPy                       |
| ML Models        | Scikit-learn, XGBoost, LightGBM     |
| Visualization    | Matplotlib, Seaborn                 |
| Imbalance Handling| imbalanced-learn (SMOTE, etc.)     |
| Environment      | Jupyter Notebook                    |

---

## 🧪 Models Implemented

- Logistic Regression  
- Random Forest  
- XGBoost  
- LightGBM  
- Gradient Boosting Classifier  

**Evaluation Metrics**:
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- Confusion Matrix  

---

## 📊 Sample Results

| Model              | Precision | Recall | F1 Score | ROC-AUC |
|--------------------|-----------|--------|----------|---------|
| Logistic Regression| 0.92      | 0.84   | 0.88     | 0.96    |
| XGBoost            | 0.95      | 0.89   | 0.92     | 0.98    |
| LightGBM           | 0.96      | 0.90   | 0.93     | 0.985   |

---

## 🙌 Acknowledgments
- Kaggle Dataset by Kartik2112
- Scikit-learn documentation
- imbalanced-learn library

## 🙋‍♂️ Author

Kardam Singhal  
🔗 [LinkedIn](https://www.linkedin.com/in/kardamsinghal)  
📫 Email: kardamsinghalllll@gmail.com

## 📄 License
This project is licensed under the MIT License – see the LICENSE file for details
