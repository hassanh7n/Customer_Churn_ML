# Customer Churn Prediction — Telecom Dataset

## 🚀 Project Overview
This project predicts customer churn for a telecom company using machine learning. The goal is to identify customers likely to leave (churn) and provide actionable insights to reduce churn.

**Dataset:** Customer information including demographics, services subscribed, tenure, billing, and payment methods.

---

## 📊 Business Questions
- What percentage of customers churn?
- Do new customers churn more than long-term ones?
- Does contract type affect churn?
- Are high-paying customers more likely to churn?
- Which services increase/decrease churn risk?
- Which customers should the business target for retention?
- Any data quality issues?

---

## 🧹 Data Cleaning & Feature Engineering
- Missing values handled
- Categorical variables encoded using one-hot encoding
- Numerical features scaled where necessary
- Target variable: `Churn` (0 = No, 1 = Yes)

---

## 📈 Exploratory Data Analysis
- Visualized churn distribution
- Explored tenure, monthly charges, and total charges vs churn
- Investigated impact of services, contract types, and payment methods

---

## 🤖 Modeling
**Models Evaluated:**
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost (final model)

**Final Model:**
- **XGBoost (tuned)**
- Recall (churners) = 86%
- Threshold adjusted for business cost trade-off

**Feature Importance Highlights:**
- Contract type (month-to-month highest churn)
- Tenure (shorter tenure higher risk)
- Monthly charges (higher charges increase churn)
- Payment method (Electronic Check risk factor)
- Services like Online Security & Tech Support reduce churn

---

## 📊 Visualizations
- Feature importance bar chart
- Confusion matrix heatmap


---

## 💡 Business Recommendations
- Target customers on **month-to-month contracts** for retention campaigns
- Focus on **new customers (short tenure)** in early months
- Offer **bundles or discounts** to high monthly charge customers
- Use model predictions to prioritize high-risk customers

---

