# 🏦 Bank Marketing Campaign Prediction

Predicting customer responses to a bank’s marketing campaign using advanced ensemble learning techniques.

---

## 📘 Overview
This project was developed for the **Kaggle Playground Series S5E8** competition.  
The objective is to predict whether a client will subscribe to a term deposit based on demographic and behavioral attributes.

---

## 🧠 Key Features
- **Exploratory Data Analysis (EDA):**  
  - Analyzed 40K+ customer records to uncover behavioral and demographic trends.
  - Visualized correlations between age, balance, campaign interactions, and response rate.

- **Feature Engineering:**  
  - Encoded categorical variables and handled class imbalance.  
  - Created interaction features to capture nuanced campaign behavior.

- **Model Development:**  
  - Implemented optimized **LightGBM**, **XGBoost**, and **CatBoost** models.  
  - Utilized **Optuna** for hyperparameter tuning with early stopping and pruning for efficiency.  
  - Combined models through **bagging ensemble** for improved stability and accuracy.

---

## 🚀 Results
| Model | ROC-AUC Score |
|:------|:--------------:|
| LightGBM | **0.972** |
| Ensemble (LGBM + XGB + CatBoost) | **0.971** |

---

## ⚙️ Tech Stack
- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, LightGBM, XGBoost, CatBoost, Optuna  
- **Tools:** Kaggle, Jupyter Notebook  

---

## 📂 Repository Structure
```
├── lightgbm-final.ipynb              # Final optimized LightGBM model
├── xgboost-catboost-lightgbm.ipynb   # Ensemble model notebook
└── README.md                         # Project documentation
```

---

## 📈 Future Improvements
- Integrate stacking ensemble for further performance gains.  
- Add SHAP-based explainability for model interpretation.  
- Deploy as a web-based prediction app using Streamlit or FastAPI.

---


---
