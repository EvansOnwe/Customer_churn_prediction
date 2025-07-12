# Customer Churn Prediction

This project focuses on predicting customer churn using machine learning, based on real-world customer behaviour data from a fictional banking scenario. The goal is to help business stakeholders, such as Lloyds Banking Group, proactively identify and retain at-risk customers through interpretable and actionable insights.

## 📊 Project Objectives

- Identify customers likely to churn
- Use historical and behavioural data to build a predictive model
- Improve model accuracy and interpretability
- Support retention strategies with data-driven insights

---

## 📁 Dataset Overview

The project uses data from five sources:

1. **Customer Demographics** – Age, gender, marital status, income
2. **Transaction History** – Spend amounts, frequency, product categories
3. **Customer Service** – Interactions, resolution status
4. **Online Activity** – Login frequency, service channels
5. **Churn Status** – Target variable (1 = churned, 0 = retained)

---

## 🧹 Data Preparation

- Missing values handled (e.g., imputation or zero-fill)
- Features engineered (e.g., total spend, unresolved issues)
- One-hot encoding for categorical variables
- Normalisation using Min-Max scaling
- Added new features like `days_since_last_login`

---

## 🧠 Machine Learning Models

- **Logistic Regression** (with class balancing)
- **Random Forest Classifier** (selected for best trade-off)
- Evaluated using:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Score

---

## ✅ Key Results

- Logistic Regression: High accuracy but poor recall for churn
- Random Forest: Balanced precision and recall with improved F1 and ROC-AUC
- Feature importance revealed top churn drivers (e.g., login recency, unresolved issues)

---

## 🚀 Business Application

The model enables SmartBank or Lloyds Banking Group to:

- Proactively target high-risk customers
- Tailor retention campaigns
- Integrate model outputs into CRM and support tools

---

