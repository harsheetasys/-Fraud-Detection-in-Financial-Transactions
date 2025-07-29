# 🛡️ Fraud Detection in Financial Transactions

## 📌 Overview

This project builds a **robust, interpretable fraud detection system** using both **Machine Learning** (Random Forest) and **Deep Learning** (Neural Network).

> 🚀 Final ROC-AUC: **0.99+**  
> 🔍 SHAP interpretability added  
> 📊 Real-world fraud insights + model tuning

---

## 🎯 Problem Statement

Financial fraud is a major risk in digital transactions.  
This project uses supervised learning techniques to **identify suspicious transactions** before damage occurs.

---

## 🧠 Models Used

| Model              | ROC-AUC | Remarks                            |
|-------------------|---------|------------------------------------|
| Random Forest      | ~0.987  | Interpretable, fast                |
| Neural Network     | ~0.991  | Captures nonlinear patterns        |

Hyperparameter tuning done using:
- `RandomizedSearchCV` (RF)
- `KerasTuner` alternative: manual grid + validation split (NN)

---

## 🔬 Key Features

- ✅ Data cleaning & outlier handling
- ✅ Class imbalance handling
- ✅ Feature engineering (balance diffs, flags)
- ✅ SHAP-based feature importance
- ✅ ROC curve & classification metrics
- ✅ Infrastructure recommendations

---

## 🖼️ Sample Visualizations

📉 Fraud by Transaction Type  
📊 Amount Distribution  
⚙️ SHAP Beeswarm Plot  
🧠 Feature Importance (Random Forest)

> See in the .ipynb file itself.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- TensorFlow / Keras
- SHAP
- Jupyter Notebook

---

