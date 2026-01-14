# Credict-Card-Fraud-Detection-ML-

💳 Credit Card Fraud Detection using Machine Learning
📌 Project Overview

Credit card fraud is a major challenge for financial institutions due to the high imbalance between normal and fraudulent transactions.
The goal of this project is to build a machine learning–based classification system that can accurately identify fraudulent credit card transactions using historical data.

The model analyzes transaction patterns and helps flag suspicious behavior early, reducing financial risk and losses.

🚀** Key Challenges Addressed**

Handling highly imbalanced datasets (fraud ≈ 0.02% of transactions)

Achieving high precision to reduce false positives

Maintaining high recall to detect as many fraud cases as possible

Using evaluation metrics suitable for imbalanced classification problems


🛠️** Technologies Used**

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

🧠 Project Workflow
1️⃣ Import Libraries

Essential libraries for data processing, visualization, and modeling are imported.

2️⃣ Load & Explore Data

Load dataset using Pandas

Explore structure using .head() and .describe()

3️⃣ Class Distribution Analysis

Separate fraudulent and valid transactions

Compute fraud ratio to understand dataset imbalance

4️⃣ Transaction Amount Analysis

Compare amount statistics for fraud vs. normal transactions

Fraudulent transactions tend to have higher average amounts

5️⃣ Correlation Analysis

Visualized feature correlations using a heatmap

Identified weak correlations due to anonymized features

6️⃣ Data Preparation

Features (X) and target (y) separated

Dataset split into 80% training and 20% testing

7️⃣ Model Training

Trained a Random Forest Classifier

Chosen for robustness and ability to handle complex patterns

8️⃣ Model Evaluation

Evaluation performed using metrics suitable for imbalanced datasets:

Accuracy

Precision

Recall

F1-score

Matthews Correlation Coefficient (MCC)

Confusion Matrix

📊 Model Performance
Metric	Score
Accuracy	0.9996
Precision	0.9873
Recall	0.7959
F1-Score	0.8814
MCC	0.8863
🔍 Interpretation

High accuracy due to class imbalance (can be misleading)

High precision → Very few false positives

Strong recall → Most fraud cases detected

High MCC → Balanced and reliable performance

📈 Confusion Matrix

A heatmap visualization is used to clearly show:

True Positives (Correct fraud detections)

False Positives (False alarms)

False Negatives (Missed fraud cases)

True Negatives (Correct normal transactions)

🏁 Conclusion

This project demonstrates:

Practical handling of imbalanced classification problems

Importance of precision, recall, and MCC in fraud detection

Effective use of Random Forests for real-world financial data

It provides a solid foundation that can be extended using:

SMOTE / resampling techniques

XGBoost or LightGBM

Time-series behavior analysis

Real-time fraud detection systems

📌 Future Improvements

Apply class balancing techniques (SMOTE, undersampling)

Hyperparameter tuning

Compare with Logistic Regression and XGBoost

Deploy model using Flask or FastAPI
