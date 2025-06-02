# 🏥 Clinical Claims Fraud Detection System

Detecting fraudulent healthcare providers using supervised machine learning, SHAP explainability, and Power BI visualizations.

---

## 📌 Project Summary

This project builds a supervised machine learning pipeline to detect fraudulent healthcare providers using a real-world clinical claims dataset. The goal is to identify providers with suspicious claim behavior by analyzing inpatient/outpatient claims, patient conditions, and reimbursement data.

✅ **91% accuracy**  
✅ **88% precision**  
✅ **ROC-AUC: 0.94**  
✅ **Power BI dashboard for fraud insights**

---

## 📂 Folder Structure

```
clinical-claims-fraud-detection/
│
├── notebooks/                 # Jupyter notebooks for EDA and modeling
├── outputs/                   # SHAP plots, feature importance, Power BI screenshots
├── data/                      # NO raw data; link provided
│   └── README.md
├── scripts/                   # Utility scripts for training and preprocessing
├── requirements.txt           # Python package dependencies
└── README.md                  # This file
```

---

## 📊 Tech Stack

- **Python**: pandas, scikit-learn, shap, imbalanced-learn
- **ML Model**: Random Forest (with SMOTE)
- **Explainability**: SHAP (Shapley values)
- **Visualization**: Power BI
- **Data**: [Healthcare Provider Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis)

---

## 🔍 Features Engineered

- Provider-level aggregation of claim behavior
- Inpatient vs outpatient claim ratios
- Chronic condition summaries
- Reimbursement and deductible patterns
- Fraud risk scores per provider

---

## 📈 Results

- **Model Performance**:  
  - Accuracy: 91%  
  - Precision: 88%  
  - ROC-AUC: 0.94

- **SHAP Feature Importance**:
  - Chronic condition flags
  - Claim type ratios
  - Annual deductible patterns

---

## 📊 Power BI Dashboard

Includes:
- Fraud probability by provider
- Geographic fraud heatmap
- High-risk claim types
- Filterable by claim type, state, fraud prediction

> 📷 Screenshot: See `outputs/powerbi_dashboard.png`

---

## 📥 How to Run

1. Clone this repo
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open notebooks in `/notebooks/` to explore code
4. Use `fraud_predictions_for_powerbi.csv` in Power BI to explore insights

---

## 🧠 About Me

I'm an aspiring data scientist transitioning from mainframe healthcare systems to applied machine learning. This is the first in a series of projects solving real-world healthcare problems.

---

## 📄 License

This project is licensed for educational and portfolio purposes.
