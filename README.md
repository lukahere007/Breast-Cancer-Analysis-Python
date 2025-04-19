# Breast-Cancer-Analysis-Python
# 🔍 Breast Cancer Logistic Regression Analysis

This project investigates the effectiveness of logistic regression in predicting breast cancer malignancy using imaging features extracted from digitized fine-needle aspirate (FNA) data. The data is sourced from the [UCI Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data).

Both **R** and **Python** implementations are provided for educational and comparative purposes.

---

## 📊 Final Model Summary

**Selected Predictors:**
- `texture_mean`
- `concavity_mean`
- `radius_mean`

**Final Model Equation (Python output):**
logit(p) = -0.47 + 0.82texture_mean + 1.29concavity_mean + 2.29*radius_mean

---

## ✅ Test Set Evaluation

| Metric               | Value |
|----------------------|-------|
| **Accuracy**         | 0.91  |
| **AUC (ROC)**        | 0.9835 |
| **Precision (Benign)**   | 0.93  |
| **Recall (Benign)**      | 0.93  |
| **Precision (Malignant)** | 0.88  |
| **Recall (Malignant)**   | 0.88  |

---

## 📈 Visual Summary

- ROC Curve confirms excellent classification performance.
- Logistic curve illustrates the impact of `texture_mean` on malignancy probability, annotated with the final equation.

---

## 📎 Additional Resources

- 📘 Full R Markdown Report: [RPubs Report](https://rpubs.com/lukahere007/breast-cancer-logistic-regression)
- 👤 LinkedIn: [Luke Wamalwa](https://www.linkedin.com/in/luke-wamalwa-839624292)

---

> *This project is part of a master's portfolio demonstrating proficiency in applied statistics and machine learning with clinical datasets.*

