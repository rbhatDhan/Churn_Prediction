# Customer Churn Prediction

## 📌 What is this project?
This project predicts whether a customer is likely to leave (churn) a telecom service using machine learning.

👉 Churn means when a customer stops using a service.  
Companies use churn prediction to identify customers who might leave and take actions to retain them.

---

## 🎯 Problem Statement
Given customer data such as tenure, monthly charges, and contract type, the goal is to predict:

➡️ Will the customer churn? (Yes / No)

This is a **binary classification problem**.

---

## 📊 Dataset
The dataset contains customer information such as:
- Tenure (how long the customer stayed)
- Monthly Charges
- Total Charges
- Contract Type
- Internet Service
- Payment Method
- Churn (Target Variable)

---

## ⚙️ Technologies Used
- Python
- Pandas & NumPy → data handling
- Matplotlib & Seaborn → visualization
- Scikit-learn → machine learning models
- XGBoost → advanced model

---

## 🔄 Project Workflow

### 1. Data Loading
Loaded the dataset using pandas.

### 2. Data Cleaning
- Converted incorrect data types (e.g., TotalCharges)
- Handled missing values using `errors='coerce'`

### 3. Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Studied relationships between features (e.g., tenure vs churn)
- Used visualizations for better understanding

### 4. Feature Engineering
- Converted categorical variables into numeric form
- Used encoding techniques like label encoding / one-hot encoding

### 5. Train-Test Split
- Split data into training and testing sets (80:20)

### 6. Model Training
Trained multiple models:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

### 7. Model Evaluation
Used multiple metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### 8. Result
XGBoost performed the best due to its ability to handle complex patterns and nonlinear relationships.

---

## 📈 Key Insights
- Customers with **low tenure** are more likely to churn
- **Month-to-month contracts** have higher churn rates
- **Higher monthly charges** may increase churn probability

---

## 📁 Project Structure
- `notebook/` → Jupyter Notebook (analysis and model)
- `data/` → Dataset
- `model/` → Saved model file
- `requirements.txt` → Required libraries

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install dependencies
