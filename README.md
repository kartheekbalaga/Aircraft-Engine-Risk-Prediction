# ✈️ Aircraft Engine Risk Prediction

A time-aware aircraft engine risk prediction system using Logistic Regression, probabilistic degradation modeling, and SHAP-based explainable AI.

---

## 📌 Project Overview

This project builds a time-aware aircraft engine risk prediction system using synthetic multi-sensor data. A probabilistic sigmoid-based degradation mechanism is used to simulate realistic engine health behavior under varying flight conditions.

The system integrates domain-driven feature engineering, rolling time-based features, and chronological train-test splitting to prevent future data leakage and simulate real-world predictive maintenance deployment.

---

## 🧠 Problem Statement

Aircraft engines operate under dynamic mechanical and environmental conditions. Early detection of engine risk is critical for predictive maintenance and operational safety.

This project aims to develop an interpretable machine learning model capable of identifying high-risk engine states using multi-sensor data while ensuring temporal validation and model transparency.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP (Explainable AI)

---

## 🛠 Key Features

- Probabilistic risk generation using sigmoid-based degradation modeling
- Domain-engineered stress indicators:
  - Thermal Stress
  - Lubrication Risk
  - Mechanical Stress
  - Degradation Score
- Rolling time-based feature modeling
- Time-aware train-test split (no future leakage)
- Segment-wise altitude performance analysis
- SHAP-based model interpretability

---

## 📊 Model Performance

- **Accuracy:** 87.4%
- **ROC-AUC:** 0.876
- **Precision (Risk):** 89.9%
- **Recall (Risk):** 85.6%
- **F1-Score:** 0.877

### Segment-wise Recall
- **High Altitude:** 83.8%
- **Low Altitude:** 88.9%

---

## 🔍 Explainability

SHAP (SHapley Additive exPlanations) is used to interpret feature-level contributions to risk prediction, improving transparency and model trustworthiness.

---

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/kartheekbalaga/Aircraft-Engine-Risk-Prediction.git