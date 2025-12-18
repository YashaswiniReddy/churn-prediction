
#  Telecom Customer Churn Prediction

This project aims to predict whether a telecom customer will churn (leave the service) using supervised machine learning. By identifying high-risk customers in advance, telecom companies can take proactive steps to retain them.

---

##  Problem Statement

Customer churn is a significant concern in the telecom industry. Retaining existing customers is often more cost-effective than acquiring new ones. This project uses historical customer data to build a predictive model that identifies churn patterns based on customer demographics, services, and account details.

---

##  Dataset

- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** ~7,000 records
- **Features include:**
  - Customer demographics (gender, senior citizen, dependents)
  - Service details (internet service, online security, tech support)
  - Account details (contract type, tenure, charges, payment method)
  - Churn label (target)

---

##  Techniques Used

- Data Cleaning & Preprocessing
- Feature Engineering (One-Hot Encoding, Scaling)
- Exploratory Data Analysis (EDA)
- Model Training (Random Forest Classifier)
- Model Evaluation (Accuracy, Precision, Recall, Confusion Matrix)
- Feature Importance Analysis

---

##  Model Performance

| Metric              | Score   |
|---------------------|---------|
| Accuracy            | 93.4%   |
| Precision (Churn)   | 88%     |
| Recall (Churn)      | 87%     |
| F1 Score (Churn)    | 87%     |

---

##  Top 5 Drivers of Churn

Based on feature importance from Random Forest:

1. **Contract Type** – Month-to-month customers churn more than those on yearly contracts  
2. **Tenure Months** – Customers with shorter tenure churn more  
3. **Monthly Charges** – High bills are linked to higher churn  
4. **Online Security** – Lack of security service is a churn risk  
5. **Tech Support** – Customers without support tend to leave more



