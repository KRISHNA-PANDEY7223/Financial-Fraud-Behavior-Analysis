# 💳 Financial Fraud Detection – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on analyzing a financial transaction dataset to identify patterns and insights related to fraudulent activity. The goal is to understand how different behavioral, transactional, and device-related features influence fraud occurrence.

The analysis is performed using **Python (Pandas, Matplotlib, Seaborn)** and is primarily exploratory in nature.

---

## 📊 Dataset Description

The dataset contains transaction-level information including user behavior, device signals, and transaction attributes.

### Key Features:

- `transaction_id` – Unique transaction identifier  
- `transaction_amount` – Amount of the transaction  
- `login_attempts` – Number of login attempts before transaction  
- `device_risk_score` – Risk score associated with device usage  
- `transfer_frequency` – Frequency of fund transfers  
- `anomaly_score` – Score indicating unusual behavior  
- `account_age_days` – Age of the account in days  
- `transaction_time_hour` – Hour of transaction  
- `failed_transactions_last_30d` – Failed transactions in last 30 days  
- `avg_monthly_balance` – Average monthly account balance  
- `daily_transaction_count` – Number of transactions per day  
- `geo_distance_km` – Geographic distance from usual location  
- `session_duration_minutes` – Session duration  
- `transaction_velocity_score` – Speed of transaction behavior  
- `card_present_flag` – Whether card was physically present  
- `international_transaction_flag` – Whether transaction is international  
- `suspicious_ip_flag` – Whether IP is flagged as suspicious  
- `fraud_flag` – Target variable (1 = Fraud, 0 = Not Fraud)

---

## 🎯 Objectives

- Understand patterns in fraudulent vs non-fraudulent transactions  
- Identify key drivers of fraud behavior  
- Analyze relationships between behavioral and transactional features  
- Evaluate how different variables interact with fraud occurrence  

---

## 🔍 Exploratory Data Analysis (EDA) Performed

### 1. Fraud Distribution Analysis
- Overall fraud percentage in dataset
- Fraud distribution across payment channels

### 2. Payment Channel Insights
- Fraud rate comparison across:
  - ATM
  - Mobile App
  - Web Banking
  - POS Terminal

### 3. Behavioral Analysis
- Transfer frequency vs anomaly score relationship
- Daily transaction count impact on fraud
- Login attempts and suspicious behavior patterns

### 4. Device & Security Signals
- Suspicious IP vs fraud relationship
- Device risk score contribution to fraud detection

### 5. Time-Based Analysis
- Transaction patterns across different hours of the day

### 6. Feature Interaction Analysis
- Cross-analysis between:
  - Anomaly score
  - Transfer frequency
  - Fraud flag
  - International transaction flag

---

## 📈 Key Insights

- Fraud transactions are distributed across all payment channels with slight variation (~11%–13%)
- No strong relationship between international transactions and fraud behavior (~50/50 split)
- Suspicious IP alone does not significantly differentiate fraud patterns
- Higher anomaly scores show more irregular and scattered behavioral patterns
- Fraud is not driven by a single feature but by **combinations of behavioral signals**
- Features like anomaly score and device risk are more informative than basic categorical flags

---

## 🧠 Conclusion

Fraud detection is a **multi-factor problem** where no single feature strongly determines fraudulent behavior. Instead, fraud emerges from subtle interactions between behavioral patterns, device risk, and transaction anomalies.

This analysis highlights the importance of:
- Feature engineering
- Interaction-based analysis
- Behavioral pattern detection

---

## 🛠️ Tools & Libraries Used

- Python   
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📌 Future Improvements

- Build a machine learning model for fraud prediction  
- Handle class imbalance using SMOTE or undersampling  
- Feature importance analysis using Random Forest / XGBoost  
- Deploy dashboard using Streamlit or Power BI  
- Real-time fraud detection system simulation  

---


## 🚀 Author

**Krishna Pandey**  
Data Analyst / Data Science Enthusiast  

---

## ⭐ If you like this project

Feel free to star ⭐ the repository and connect!
