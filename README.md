# 🫀 Heart Stroke Prediction Using Machine Learning

## 📌 Project Overview
This project predicts whether a person is at risk of stroke based on various health indicators. It uses supervised machine learning models trained on a publicly available dataset.

---

## 📊 Dataset
- **Source**: [Kaggle Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **Target**: `stroke` (1 = stroke occurred, 0 = no stroke)
- **Features**: 
  - Demographics: `gender`, `age`, `ever_married`, `Residence_type`
  - Health: `hypertension`, `heart_disease`, `avg_glucose_level`, `bmi`
  - Lifestyle: `work_type`, `smoking_status`

---

## 🧠 Models Used
- Logistic Regression
- Random Forest ✅ *(Best Accuracy)*
- XGBoost
- SVM

---

## 📈 Evaluation Metrics
- Accuracy
- Precision, Recall, F1 Score
- ROC-AUC

---

## ⚙️ How to Run the Project

### 1. Install Requirements
```bash
pip install -r requirements.txt
