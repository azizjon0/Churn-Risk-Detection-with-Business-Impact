# 📉 Customer Churn Prediction with Logistic Regression

This project aims to identify customers who are likely to **churn** (leave the company) and estimate the **potential business impact** using machine learning and financial metrics such as **LTV** (Customer Lifetime Value).

---

## 🔍 Problem Overview

Telecom companies lose significant revenue when customers cancel their subscriptions.  
This project predicts the probability of churn using customer features (e.g., contract type, services used, payment method), and provides **business insights** for retention strategies.

---

## 🛠️ Methodology

- ✅ **Model**: Logistic Regression  
- 🔄 **Validation**: Stratified K-Fold Cross-Validation (5 folds)  
- 📊 **Metrics**: Accuracy, AUC, F1-Score, ROC Curve, Calibration Curve  
- 📦 **Libraries**: `scikit-learn`, `pandas`, `seaborn`, `matplotlib`, `ydata-profiling`

---

## 📈 Key Results

- **Model AUC (ROC)**: 0.847  
- **High-risk group churn rate**: 97.1%  
- **Avg. LTV of high-risk group**: $435  
- **Estimated revenue loss**: $271,499  
- **Potential savings (30% retention)**: $81,450  

---

## 📊 Business Insights

- 📉 Customers with **monthly contracts** and **electronic check payments** are most likely to churn.
- 💳 Customers on **automatic payment methods** have **higher LTV** and **lower churn**.
- 🎯 Retention strategies should focus on **high-risk, high-value** segments.

---

## 📁 Project Structure

├── data/ # Input datasets
├── notebooks/ # Jupyter notebooks with EDA & modeling
├── outputs/ # Plots and results
└── README.md # Project overview




## 🚀 How to Run

1. Clone the repo  
2. Install dependencies  
3. Run the notebooks in order:
    - `01_eda.ipynb`
    - `02_modeling.ipynb`
    - `03_business_analysis.ipynb`

---

## 📌 Future Work

- Test more advanced models (Random Forest, XGBoost)
- Automate LTV + churn dashboard
- A/B test retention campaigns using model outputs

---

## 👤 Author

**Your Name**  
Machine Learning & Data Science Enthusiast  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

