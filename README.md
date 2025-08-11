# Heart-Disease-Risk-Assessment




---

## 🎯 Aim
Build a **user interface** that allows users to input health metrics and uses a **machine learning model** to predict the **risk of heart disease**.

---

## 📖 Description
This project focuses on predicting the risk of heart disease based on user-provided health metrics such as:
- Age
- Sex
- Blood Pressure
- Cholesterol Level
- Blood Sugar
- ECG Results
- Maximum Heart Rate
- Exercise-induced Angina
- Oldpeak (ST depression)
- Slope of the ST segment

A **Random Forest Classifier** (or any other ML model) is trained using a heart disease dataset.  
The model is then integrated into a **Flask** or **Streamlit** web application to provide predictions through a simple UI.

---

## 🛠 Technologies Used
- **Python**
-  **Streamlit** (for UI)
- **Scikit-learn** (for ML model)
- **Pandas**, **NumPy** (for data handling)
- **Matplotlib**, **Seaborn** (for data visualization)
- Joblib** (for model saving and loading)

---

## 📂 Project Structure
HEART_DISEASE_PROJECT/
│
├── app/
│   └── app.py
│
├── data/
│   └── heart.csv
│
├── models/
│   └── heart_rf_pipeline.joblib
│
├── notebooks/
│   └── heart_modeling.ipynb
│
└── requirements.txt



## 📦 Installation

### 1️⃣ Clone the Repository

git clone https://github.com/yourusername/heart-disease-risk-assessment.git
cd HEART_DISEASE_PROJECT
2️⃣ Install Dependencies
pip install -r requirements.txt
▶️ Usage
If using Streamlit:

streamlit run app.py
This will open the UI in your browser.


📊 Dataset
You can use the UCI Heart Disease Dataset:
🔗 https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
or any similar dataset with relevant health metrics.

📚 What You Will Learn
Designing user-friendly interfaces for health applications

Understanding cardiovascular risk factors

Implementing and evaluating ML classification models

Integrating ML models into web applications



