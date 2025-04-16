# Maternal-Fetal-Health-Risk-Prediction


📌 Maternal-Fetal Health Risk Prediction is a Machine Learning-based system that predicts the risk level of maternal and fetal health during pregnancy. It aims to assist healthcare professionals in early detection of high-risk pregnancies using real-world medical data and predictive analytics.

👩‍⚕️ Project Features:

1️⃣ User Input Interface:
Accepts medical parameters such as:
  Age, Systolic & Diastolic BP
  Blood Sugar Levels (BS)
  Body Temperature
  Heart Rate
  Uterine Contractions
  Fetal Movements
  Fetal Heart Rate
  Risk Level (for training)

2️⃣ Model Development & Training:
Data preprocessing: Handling missing values, normalization, encoding
Utilizes maternal-fetal health datasets (e.g., from Kaggle or hospitals)
Implements and compares various ML models:
  Random Forest
  Logistic Regression
  XGBoost
  Decision Tree
Evaluated using classification metrics:
Accuracy, Precision, Recall, F1-Score, Confusion Matrix

3️⃣ Prediction Output:
Predicts one of the three risk levels:
  Low Risk
  Mid Risk
  High Risk
Displays prediction along with confidence level
