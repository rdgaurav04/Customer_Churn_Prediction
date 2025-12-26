# Customer Churn Prediction – DTH / E-Commerce
End-to-end customer churn prediction project with EDA, feature engineering, ML modeling, and data-driven retention recommendations.


## 📌 Business Problem
Customer churn is a major challenge in highly competitive DTH/E-commerce markets. 
Since one account may include multiple users, losing a single account can result in 
significant revenue loss.

The objective of this project is to:
- Predict customer churn
- Identify high-risk customers early
- Provide actionable, revenue-safe retention strategies

---

## 📊 Dataset Overview
- Records: 11,260 accounts
- Target Variable: `Churn` (1 = Yes, 0 = No)
- Key Features:
  - Tenure
  - Complaints
  - Agent Satisfaction Score
  - Revenue per User
  - Account Segment

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights:
- ~16.8% customers churned
- Early-tenure customers (≤6 months) show highest churn
- Complaints + low agent scores significantly increase churn risk
- High revenue does NOT guarantee loyalty

---

## 🛠 Data Preprocessing
- Missing value treatment (median/mode)
- Outlier handling using IQR capping
- Feature engineering:
  - `tenure_group`
  - `rev_per_user`
  - `is_high_risk`
  - `complain_lowscore`
- One-hot encoding & standard scaling

---

## 🤖 Models Implemented
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### 📈 Model Performance
- Business priority: **High Recall**
- Best Models:
  - **Random Forest**
  - **XGBoost**
- ROC-AUC ≈ **0.99**

---

## 💡 Business Recommendations
- Strengthen onboarding for first-6-month customers
- Improve complaint resolution & agent training
- Deploy churn model in CRM for proactive outreach
- Use value-added services instead of heavy discounts
- Create segment-specific retention campaigns

---

## 🚀 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

---

## 📁 Project Structure
