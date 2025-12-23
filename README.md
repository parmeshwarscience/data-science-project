Insurance Charges Prediction using Machine Learning

This project predicts medical insurance charges based on customer information such as age, BMI, smoking status, number of children, gender, and region.
The goal is to build a clean, production-ready Machine Learning pipeline with proper preprocessing, feature engineering, and evaluation.

Dataset Information

Source: Insurance dataset

Rows: 1338

Features:

age

sex

bmi

children

smoker

region

charges (target variable)

Removed duplicate records

Encoded categorical variables:

sex → binary encoding

smoker → binary encoding

region → One-Hot Encoding

Feature scaling using StandardScaler

BMI categorization:

Underweight

Normal

Overweight

Obese

