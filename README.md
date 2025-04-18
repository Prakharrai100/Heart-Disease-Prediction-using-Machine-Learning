# Heart-Disease-Prediction-using-Machine-Learning
The objective is to develop a machine learning model that predicts whether a patient has heart disease based on medical parameters such as age, cholesterol, blood pressure, and more.
💓 Heart Disease Prediction Using Machine Learning
This project uses machine learning techniques to classify whether a patient has heart disease based on medical features. It compares models and visualizes performance using ROC curves and feature importance.

📁 Dataset
The dataset includes common medical attributes such as:

Age, Sex

Resting Blood Pressure

Cholesterol

Fasting Blood Sugar

ECG Results

Maximum Heart Rate Achieved

Exercise Induced Angina

ST Depression

Target (0 = No Heart Disease, 1 = Heart Disease)

📌 Source: UCI Heart Disease dataset or similar.

🔧 Technologies Used
Python

Google Colab

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🧪 Project Workflow
1. Data Upload
Upload the CSV file through the Colab interface.

2. Data Preprocessing
Null value checks

Feature scaling using StandardScaler

3. Model Training
Trained and evaluated two models:

Logistic Regression

Random Forest Classifier

4. Evaluation Metrics
Accuracy Score

ROC AUC Score

Confusion Matrix

Classification Report

ROC Curve Plots

5. Feature Importance
Visualized using bar charts (only for Random Forest).

📊 Example Results
Logistic Regression Accuracy: ~84%

Random Forest Accuracy: ~88%

Best AUC: Random Forest (~0.92)

(Values may vary slightly based on train/test split)

📂 Files Included
heart_disease_prediction.ipynb — Main notebook

4. Predict Heart Disease.csv — Dataset used

Heart_Disease_Project_Report_Final.docx — Full project report (Title page, intro, code, results)

README.md — This file

🧾 References
UCI Machine Learning Repository

Scikit-learn documentation

Matplotlib and Seaborn official docs

