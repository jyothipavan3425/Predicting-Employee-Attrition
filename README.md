# 📊 Predicting Employee Attrition Using Machine Learning

This project focuses on building a machine learning system to predict **Employee Attrition** using the IBM HR Analytics dataset.  
The project applies advanced ML techniques, performs data preprocessing, handles class imbalance with SMOTE, and uses LIME for model interpretability.

---

## 🚀 Project Overview
Employee attrition is one of the biggest challenges for HR teams.  
This project develops a predictive model to help organizations:

- Identify employees with a high risk of leaving  
- Understand key factors that influence attrition  
- Support HR planning and retention strategies  

The analysis is performed using **R programming**, and multiple models are compared for best performance.

---

## 🧠 Machine Learning Methods Used

### ✔ Logistic Regression  
Simple baseline model to understand important predictors.

### ✔ Decision Tree  
Provides hierarchical rules for decision-making.

### ✔ Random Forest  
Ensemble model for higher accuracy and robustness.

### ✔ XGBoost  
Gradient boosting model providing the best performance.

### ✔ Support Vector Machine (SVM)  
Useful for separating complex boundaries.

### ✔ SMOTE (Synthetic Minority Oversampling Technique)  
Used to fix class imbalance (Attrition = Yes is very low).

### ✔ LIME (Local Interpretable Model-Agnostic Explanations)  
Used to explain model predictions and improve interpretability.

---

## 🧹 Data Preprocessing

The following techniques were applied:

- Handling missing values  
- Label encoding categorical variables  
- One-hot encoding for multi-class values  
- Train-test split  
- Feature scaling (where required)  
- SMOTE balancing for minority class  

Dataset used: **IBM HR Employee Attrition Dataset (public Kaggle dataset)**

---

---

## 📊 Exploratory Data Analysis (EDA)

✔ Distribution of categorical and numeric variables  
✔ Correlation Heatmap  
✔ Attrition vs. Job Satisfaction  
✔ Attrition by Age, Gender, Department  
✔ Boxplots showing salary differences  

Key insights from EDA:

- Younger employees show higher attrition  
- Lower job satisfaction correlates strongly with attrition  
- Employees with less time at the company are more likely to leave  
- OverTime has high impact on attrition  

---

## 🏆 Model Performance Summary

| Model               | Accuracy | Precision | Recall | F1 Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | ~82%     | Moderate  | Low    | Moderate |
| Decision Tree       | ~86%     | Good      | Moderate | Good   |
| Random Forest       | ~91%     | High      | High   | High     |
| XGBoost             | **~93%** | **Highest** | **Highest** | **Best** |
| SVM                 | ~87%     | Good      | Moderate | Good   |

👉 **XGBoost performs the best after applying SMOTE.**

---

## 🧾 LIME Model Interpretability

LIME reveals which factors influenced individual employee predictions.

Common important features:

- Monthly Income  
- Job Satisfaction  
- OverTime  
- Total Working Years  
- Environment Satisfaction  
- Business Travel  

LIME visualizations help HR teams understand *why* the model predicts attrition.

---

## 🔧 How to Run the Project

### 1️⃣ Install required R libraries:
```r
install.packages(c("tidyverse", "caret", "DMwR", "e1071", "randomForest", "xgboost", "lime"))

👤 Author

Jyothi Pavan Kutala
MS Data Science, University of Massachusetts Dartmouth

