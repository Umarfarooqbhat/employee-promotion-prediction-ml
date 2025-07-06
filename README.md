# 🧠 Employee Promotion Prediction (ML Project)

This project aims to predict which employees are most likely to be promoted based on their past performance, training scores, and key HR metrics. The goal is to help HR teams make data-driven, fair, and efficient promotion decisions.

## 🔍 Project Overview

- **Domain**: Human Resources / HR Analytics
- **Objective**: Build a machine learning model to classify employees into "Promoted" or "Not Promoted"
- **Dataset Size**: 23,490 records
- **Target Variable**: `is_promoted`

## 🧪 Techniques Used

- Exploratory Data Analysis (EDA)
- Feature Engineering & Preprocessing
- Feature Scaling with:
  - StandardScaler
  - MinMaxScaler
  - RobustScaler
  - MaxAbsScaler
- ML Models:
  - XGBoost
  - LightGBM
  - CatBoost
- Model Evaluation using:
  - Accuracy
  - ROC-AUC
  - Confusion Matrix
  - Classification Report

## ✅ Final Model

After comparison, **CatBoost** was chosen as the final model due to its:
- Highest accuracy of **74.40%**
- Strong ROC-AUC score of **0.748**
- Consistency across scalers
- Native handling of categorical features

## 📈 Key Insights

- **KPI Met** and **Average Training Score** are top predictors of promotion
- Employees with previous high ratings are more likely to be promoted
- KPI achievement is statistically significant (p-value < 0.05) in predicting performance

## 📊 Visuals

- Model Accuracy Comparison
- ROC-AUC Comparison
- Feature Importance (CatBoost)

## 🎯 Business Impact

This model enables HR teams to:
- Proactively identify promotable employees
- Reduce manual bias in decisions
- Increase fairness and employee satisfaction
- Improve talent retention

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- XGBoost, LightGBM, CatBoost

## 📁 Files Included

| File | Description |
|------|-------------|
| `Employee_Promotion_Model_UmarFarooq.ipynb` | Full notebook with code and analysis |
| `UmarFarooq_PromotionPrediction_Video.mp4` or `Video_Link.txt` | Final presentation video |
| `Employee_Promotion_Presentation.pdf` | Polished presentation with visuals |
| `requirements.txt` | List of Python packages used |

## 👤 Author

**Umar Farooq**  
📧 umarfrooqbhat@email.com

---

> *Built as part of a Menternship  project Teach For India.*
