# 🔑 Key Findings – Financial Fraud Detection EDA

## 1. Fraud Distribution is Relatively Balanced Across Channels
Fraud is distributed across all payment channels (ATM, Mobile App, Web Banking, POS Terminal) with only slight variation (~11%–13%). This indicates that no single payment channel is a dominant source of fraud.

---

## 2. Payment Channel is a Weak Predictor of Fraud
Although ATM and Mobile App show slightly higher fraud rates compared to POS Terminal and Web Banking, the differences are minimal. This suggests that payment channel alone is not a strong indicator of fraudulent activity.

---

## 3. International Transactions Are Not Strong Fraud Indicators
Analysis shows that international and domestic transactions are almost evenly distributed (~50/50) across both fraud and non-fraud cases. This implies that international transaction flags do not significantly contribute to fraud detection in this dataset.

---

## 4. Suspicious IP Flag Has Limited Standalone Power
Even when IP addresses are flagged as suspicious, the distribution between domestic and international transactions remains nearly identical. This indicates that suspicious IP alone is not sufficient to detect fraud.

---

## 5. Fraud is Driven by Behavioral Patterns, Not Single Features
Fraudulent activity is not strongly linked to any single variable. Instead, it emerges from combinations of behavioral and transactional features such as:
- Anomaly score
- Device risk score
- Transaction velocity
- Login attempts
- Transfer frequency

---

## 6. Anomaly Score Shows Irregular and Non-Linear Patterns
Higher anomaly score groups show more scattered and irregular behavior across transfer frequency ranges, suggesting that fraud is more behavioral and complex rather than linearly dependent on transaction frequency.

---

## 7. Legitimate Transactions Show More Stable Behavior
Non-fraud transactions show relatively uniform and stable distributions across different feature bins, indicating predictable and consistent user behavior.

---

## 8. Fraud Detection Requires Feature Interaction Analysis
Single-variable analysis is insufficient. Strong insights emerge only when combining multiple features (e.g., anomaly score + fraud flag + transfer frequency), highlighting the importance of multivariate analysis.

---

## 9. Overall Conclusion
Fraud detection in this dataset is a multi-dimensional problem where no single feature strongly determines fraud. Instead, fraud is better identified through patterns of abnormal behavior across multiple signals rather than isolated indicators.
