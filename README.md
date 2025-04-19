# 🔬 Breast Cancer Logistic Regression Analysis

This project explores the effectiveness of logistic regression models in predicting the malignancy of breast cancer tumors using digitized FNA image features. The analysis is conducted in both **R** and **Python** for comparative insights.

## 📈 Objective
To build, evaluate, and compare multiple logistic regression models for breast cancer classification using texture, concavity, and radius characteristics. The data originates from the UCI Machine Learning Repository.

## 📊 Dataset
- **Source**: [UCI Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Samples**: 569 observations
- **Features**: 30 numeric predictors (we focus on 10 mean image features)

## 🧪 Methods
- Data split: 60% Training, 20% Validation, 20% Test
- Feature selection based on statistical significance and correlation
- Model comparison using AIC, Accuracy, AUC, and LogLoss
- Final model: `logit(p) = -0.47 + 0.82*texture_mean + 1.29*concavity_mean + 2.29*radius_mean`

## ✅ Final Model (Python Test Results)
- **Accuracy**: 0.91  
- **AUC**: 0.9835  
- **Confusion Matrix**:
  - Sensitivity: 0.93  
  - Specificity: 0.88  

## 📘 Reports

- 📊 **[View R Markdown Report on RPubs](https://rpubs.com/lukahere007/breast-cancer-logistic-regression)**
- 🐍 **[View Python Notebook on GitHub](https://github.com/lukahere007/Breast-Cancer-Analysis-Python/blob/main/Breast%20Cancer%20Analysis%20in%20Python.ipynb)**


## 📎 Additional Resources


- 👤 LinkedIn: [Luke Wamalwa](https://www.linkedin.com/in/luke-wamalwa-839624292)

---

> *This project is part of a master's portfolio demonstrating proficiency in applied statistics and machine learning with clinical datasets.*

