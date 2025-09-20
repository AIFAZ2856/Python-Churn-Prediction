📊 Customer Churn Prediction (Python Project)

📌 Project Overview
This project predicts customer churn for a telecom company using machine learning.
Customer churn occurs when customers stop doing business with a company. Predicting churn helps businesses design better retention strategies and reduce revenue loss.

🛠️ Tools & Libraries Used

Python
Pandas, NumPy (Data Cleaning & Processing)
Matplotlib, Seaborn (Visualization)
Scikit-learn (ML Models)

📂 Dataset
Source: Telco Customer Churn Dataset
Rows: ~7,000 customers
Columns: 20 (Customer details, services, billing info, churn status)
Key Columns:
tenure, MonthlyCharges, TotalCharges, Contract, PaymentMethod, InternetService, Churn

🔍 Exploratory Data Analysis (EDA)

Checked for missing values and duplicates
Converted categorical columns into numeric using get_dummies()
Analyzed churn distribution by contract type, payment method, and services
Plotted correlations and churn patterns

🤖 Machine Learning Models
Logistic Regression (baseline)
Random Forest Classifier (improved model)

Evaluation Metrics:
Confusion Matrix
Precision, Recall, F1-score
ROC Curve & AUC

📊 Key Insights
Customers on Month-to-Month contracts are most likely to churn
Higher Monthly Charges correlate with higher churn risk
Longer Tenure reduces churn probability
Add-on services (Tech Support, Online Security) reduce churn

✅ Results
Accuracy: ~80%
Recall (Churn class): Improved from 54% (Logistic Regression) → 72% (Random Forest with class balancing)
Business Value: Helps the company identify at-risk customers and take proactive retention measures
<img width="646" height="533" alt="image" src="https://github.com/user-attachments/assets/a5a911d2-d338-4624-9ae1-81279c4e7579" />
<img width="533" height="446" alt="image" src="https://github.com/user-attachments/assets/a86c6ac8-a65a-4254-aa8b-bf9cef2697d9" />


