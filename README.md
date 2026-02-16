## 📉 Customer Churn Analysis & Predictive Modeling
## 📌 Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses. This project focuses on analyzing customer behavior patterns and building a predictive model to identify high-risk customers and reduce revenue loss.

The objective is to combine data analysis, SQL querying, visualization, and machine learning to provide actionable business insights.

## 🎯 Business Problem

Telecom companies face significant revenue loss when customers discontinue services. Instead of reacting after customers leave, the goal of this project is to:

Identify customers likely to churn

Understand key drivers of churn

Estimate revenue at risk

Recommend retention strategies

## 📊 Dataset

Source: IBM Telco Customer Churn Dataset (Kaggle)

Records: 7,043 customers

Features: 21 attributes including:

Demographics

Account information

Services subscribed

Payment details

Churn status (Target Variable)

## 🧹 Data Cleaning & Preprocessing

Performed using Python (Pandas):

Converted TotalCharges from object to numeric

Handled missing values

Checked and removed duplicates

Encoded categorical variables

Created new feature: TenureGroup

Prepared dataset for SQL analysis and modeling

Clean dataset saved separately to maintain raw data integrity.

## 🔍 Exploratory Data Analysis (EDA)

Analyzed churn behavior across:

Contract Type

Payment Method

Internet Service Type

Monthly Charges

Tenure Groups

## Key Insights:

Month-to-month contract customers show significantly higher churn.

Customers with electronic check payments have higher churn rates.

Low-tenure customers are more likely to churn.

Higher monthly charges correlate with increased churn probability.

## 🗄️ SQL Analysis

Performed structured queries to calculate:

Overall churn rate

Churn by contract type

Churn by payment method

Revenue impact estimation

High-risk customer segments

This demonstrates database-level analytical capability.

## 🤖 Predictive Modeling

Built classification models using:

Logistic Regression

Decision Tree

Evaluation Metrics Used:

Accuracy

Precision & Recall

Confusion Matrix

ROC Curve

The model identifies high-risk customers to enable proactive retention strategies.

## 💰 Business Impact Simulation

Estimated revenue at risk using:

Revenue at Risk =
(Number of churned customers × Average Monthly Revenue × 12)

Based on model predictions, targeted retention efforts could potentially reduce churn by 15–20%, significantly protecting annual revenue.

## 📊 Power BI Dashboard

Built an interactive dashboard highlighting:

Overall churn rate

Customer segmentation

Revenue at risk

Churn by contract & tenure

High-risk customer indicators

Dashboard enables business stakeholders to make data-driven decisions.

## 🛠️ Tech Stack

Python (Pandas, NumPy, Matplotlib, Scikit-learn)

SQL

Power BI

Excel

Git & GitHub

## 📂 Repository Structure
data/
notebooks/
sql/
powerbi/
images/
README.md
requirements.txt

## 🧠 Key Skills Demonstrated

Data Cleaning & Preprocessing

SQL-Based Business Analysis

Exploratory Data Analysis

Predictive Modeling

Business Impact Estimation

Dashboard Creation

End-to-End Project Structuring

📌 Conclusion

This project demonstrates how data analytics can be leveraged to reduce customer attrition and protect revenue. By identifying churn drivers and predicting high-risk customers, businesses can implement proactive retention strategies and improve long-term profitability
