# Customer_Churn_Analytics
Customer Churn Analytics: Predictive Business Intelligence A machine learning project using Python to analyze and predict customer churn for a telecommunications provider. Features automated feature engineering, KPI dashboarding, and a Logistic Regression model to identify key risk factors and drive retention strategies.

## 🚀 Project Overview
Customer churn is a critical metric for subscription-based businesses. This project utilizes the **Telco Customer Churn dataset** to build a predictive model that estimates the likelihood of a customer leaving the service. 

### Key Features:
* **Automated Data Cleaning:** Handles missing values and optimizes data types for analysis.
* **Feature Engineering:** Simulates signup dates and creates custom customer segments (Basic, Pro, Enterprise) based on monthly charges.
* **KPI Dashboard:** Visualizes churn distribution, revenue metrics, and customer tenure cohorts.
* **Predictive Modeling:** Implements a Logistic Regression model to classify churn risk.
* **Business Intelligence:** Ranks features by their impact on churn to guide retention offers.

## 📊 Dataset Description
The analysis uses the `WA_Fn-UseC_-Telco-Customer-Churn.csv` dataset, which contains 7,043 customer records and 21 features, including:
* **Demographics:** Gender, Senior Citizen status, Partner, and Dependents.
* **Services:** Phone, Multiple Lines, Internet (DSL/Fiber Optic), Online Security, Tech Support, and Streaming.
* **Account Info:** Tenure, Contract type, Payment Method, and Paperless Billing.
* **Financials:** Monthly Charges and Total Charges.
* **Target:** Churn (Yes/No).

## 📈 Key Insights & Recommendations
Based on the model analysis:
1.  **High-Risk Drivers:** Customers with **Month-to-Month contracts** and those using **Electronic Checks** for payment show significantly higher churn rates.
2.  **Retention Drivers:** Long-term contracts (One/Two Year) and Fiber Optic service availability are strong indicators of customer loyalty.
3.  **Plan Analysis:** The "Pro" plan tier typically experiences higher churn compared to "Basic" and "Enterprise" tiers.

### Recommended Actions:
* Target high-risk customers (Risk Score > 0.7) with specialized retention offers.
* Promote long-term contracts to stabilize the customer base.
* Improve the onboarding process for new Fiber Optic customers.
* Encourage automatic payment methods over Electronic Checks to reduce friction.

## 🧰 Technologies Used
* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (StandardScaler, LabelEncoder, Logistic Regression)
