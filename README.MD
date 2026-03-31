#📊 Customer Churn Prediction & Retention Analysis

🔍 Project Overview

This project aims to predict customer churn in a telecom dataset and identify key factors influencing customer retention. The goal is to help businesses proactively reduce revenue loss by identifying high-risk customers.

⸻

🎯 Problem Statement

Customer churn leads to significant revenue loss.
This project builds a machine learning model to:
	•	Predict whether a customer will churn
	•	Identify key drivers of churn
	•	Provide actionable business insights

⸻

📁 Dataset
	•	Dataset: Telco Customer Churn Dataset
	•	Contains ~7,000 customer records
	•	Features include:
	•	Customer demographics
	•	Service usage
	•	Contract type
	•	Billing information

⸻

🧹 Data Cleaning & Preprocessing
	•	Handled hidden missing values in TotalCharges
	•	Converted categorical target (Churn) into binary (0/1)
	•	Removed irrelevant column (customerID)
	•	Applied one-hot encoding to categorical features
	•	Ensured all features are numeric for modeling

⸻

📊 Exploratory Data Analysis (EDA)

Key insights from visualizations:
	•	📉 Dataset is imbalanced (more non-churn than churn)
	•	⏳ Customers with low tenure are more likely to churn
	•	💰 Higher monthly charges increase churn probability
	•	📄 Month-to-month contracts have the highest churn rates

⸻

🤖 Model Building

Models Used:
	•	Logistic Regression
	•	Random Forest

Evaluation Metric:
	•	Focused on Recall (important for detecting churn)

⸻

⚙️ Model Optimization
	•	Applied threshold tuning (0.3) to improve churn detection
	•	Improved recall from 0.52 → 0.73

⸻

	•	Interpretability

⸻

🔍 Feature Importance

Top factors influencing churn:
	•	Contract type
	•	Monthly charges
	•	Tenure

⸻

💡 Business Insights
	•	Customers on month-to-month contracts churn more
	•	High monthly charges increase churn risk
	•	New customers (low tenure) are more likely to leave

⸻

🏁 Conclusion

The model successfully identifies high-risk churn customers.
By prioritizing recall, the business can:
	•	Detect more potential churn cases
	•	Take proactive retention actions
	•	Reduce revenue loss

This project demonstrates the ability to build, evaluate, and optimize machine learning models aligned with real-world business objectives.

⸻

🚀 Tech Stack
	•	Python
	•	Pandas, NumPy
	•	Seaborn, Matplotlib
	•	Scikit-learn

⸻

📌 Key Skills Demonstrated
	•	Data Cleaning & Preprocessing
	•	Exploratory Data Analysis (EDA)
	•	Classification Modeling
	•	Model Evaluation (Precision, Recall, F1)
	•	Threshold Tuning
	•	Business Interpretation
