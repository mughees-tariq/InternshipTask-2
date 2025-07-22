# 📊 Customer Churn Prediction – Machine Learning Pipeline

This project implements a complete **Machine Learning pipeline** for predicting customer churn using structured data. It includes all critical stages from data preprocessing to model deployment and evaluation.

---

## 📌 Objective

To build a robust machine learning pipeline that can predict whether a customer is likely to churn (leave the service) based on historical features.

---

## 📁 Dataset

- Contains customer details and a churn label (Yes/No).
- Common features:
  - Demographic data (gender, tenure, etc.)
  - Service usage (internet, phone service)
  - Payment method, contract type
  - Target column: `Churn`

---

## ⚙️ Technologies & Libraries Used

- Python
- pandas, numpy
- scikit-learn
- joblib (for saving/loading model)
- matplotlib / seaborn (for visualization)

---

## 🔍 ML Pipeline Overview

1. **Data Loading & Preprocessing**
   - Handled missing values and categorical encoding
   - Feature scaling using `StandardScaler`

2. **Train/Test Split**
   - Stratified split to preserve class distribution

3. **Model Training**
   - Model: **Logistic Regression**
   - Wrapped in a pipeline for clean preprocessing and inference

4. **Model Evaluation**
   - Confusion matrix
   - Classification report (Precision, Recall, F1-score)
   - Accuracy score

5. **Model Persistence**
   - Final pipeline saved to `churn_pipeline.pkl` for deployment

---

## 📈 Results

- The model was evaluated using multiple classification metrics.
- Achieved satisfactory results in predicting churn vs. no churn.

---

## 📂 Files

- `ML_Pipeline.ipynb`: Main notebook for Task 2
- `churn_pipeline.pkl`: Trained and saved ML pipeline

---
