# 🧠 Credit Card Default Predictor

A machine learning project to predict the likelihood of credit card customer default, using classification models and exploratory data analysis. Built to assist financial institutions in identifying high-risk accounts and enabling proactive credit risk strategies.

---

## 📄 Project Summary

This project explores credit card customer behavior to build a **predictive model** that classifies whether a customer is likely to **default on their next payment**. It leverages classification algorithms to assess risk based on historical features like bill amount, payment history, and credit utilization. The model can help **financial institutions reduce credit losses** and make data-driven lending decisions.

---

## 📊 Key Findings

- **Payment History (PAY_0 to PAY_6)** is the most influential factor in predicting defaults.
- Customers with higher **credit limits (LIMIT_BAL)** were less likely to default.
- **Fluctuations in bill amounts** over months hinted at financial instability and higher risk.
- The dataset exhibited **class imbalance (~22% defaults)**, which was considered during evaluation.
- **Random Forest** provided the most balanced and accurate performance.
- **Logistic Regression** offered strong interpretability, suitable for compliance-driven contexts.

---

## 💡 Business Impact

If deployed in a financial organization, this model can:
- **Identify at-risk customers before default occurs**
- **Enable targeted communication or early interventions**
- **Optimize credit limits and reduce charge-off rates**
- **Improve lending strategies with data-backed insights**

---

## 🔧 Tech Stack

- **Python**: pandas, scikit-learn, seaborn, matplotlib
- **Jupyter Notebook**
- **Git / GitHub**
- **Dataset**: [UCI Credit Card Default Dataset](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

---

## 📁 Features

- Full exploratory data analysis (EDA)
- Feature correlation and scaling
- Model training with:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - SVM
- Performance metrics: Accuracy, Precision, Recall, F1-Score
- Confusion Matrix for visual performance understanding

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ChiragPhalgune/Credit-Card-Default-predictor.git
   cd Credit-Card-Default-predictor
