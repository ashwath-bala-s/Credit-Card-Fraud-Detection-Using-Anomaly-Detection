# Credit Card Fraud Detection Using Anomaly Detection

**Introduction:**

The frauds in the credit cards industry are stealing or using stolen cards, or take more an aggressive form such as account takeover, counterfeiting and much more. The magnitude of credit card frauds is growing larger each day due to ever-increasing online transactions. Anomaly detection is an unsupervised data processing technique to detect anomalies from the dataset. Anomalies are data points that stand out amongst other data points in the dataset and do not fit the normal behavior in the data. These data points or observations deviate from the dataset’s normal behavioral patterns. The anomaly detection is very useful to detect fraud transactions just like in our case.

**Problem Statement:**

The objective of this project is to develop an anomaly detection model that accurately identifies fraudulent credit card transactions based on historical transaction data. Utilizing machine learning algorithms, the model will analyze patterns in transaction behavior to distinguish between legitimate and suspicious activities.

**Dataset:**


The dataset has 2,84,807 records and has the following variables:

(i) Time: Time elapsed since the first transaction in seconds.

(iI) V1 to V28: Anonymized features derived from the original data (these could represent various transaction attributes).

(iii) Amount: The transaction amount.

(iv) Class: Indicating whether the transaction is fraudulent (1) or legitimate (0) [Target Variable]

**Project Description:**

• Utilized the PyOD (Python Outlier Detection) library for anomaly detection.

• Conducted Exploratory Data Analysis (EDA) for an in-depth understanding of credit card transactional data.

• Performed feature pre-processing prior to model building.

• Developed and evaluated Isolation Forest, Local Outlier Factor, One-Class SVM, and XGBoost models for anomaly detection.

• Compared the models using the AUC-ROC curve.

• Achieved an ROC score of 0.99 with the XGBoost model.

**Skills:** Machine Learning · Anomaly Detection · Exploratory Data Analysis · Feature Pre-Processing · PyOD · Isolation Forest Model · Local Outlier Factor Model · One Class SVM Model · XGBoost
