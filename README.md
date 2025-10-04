# 💰 Loan Approval Prediction using Machine Learning

A Machine Learning project that predicts whether a loan applicant is eligible for loan approval based on various personal and financial factors.  
This project demonstrates an end-to-end ML pipeline — from data preprocessing and model training to evaluation and deployment.

---

## 📌 Project Overview

The **Loan Prediction System** helps financial institutions automate the loan approval process by evaluating applicants’ details such as income, credit history, loan amount, and more.  
The model predicts whether the loan should be **Approved (1)** or **Not Approved (0)**.

---

## 🚀 Features

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model Training and Evaluation  
- Deployment using Streamlit / Flask  
- Interactive User Interface for predictions  

---

## 🗂 Dataset

The dataset contains applicant information including demographic, financial, and credit-related attributes.  
Below are the main features:

| Feature | Description |
|----------|-------------|
| **Loan_ID** | Unique Loan ID |
| **Gender** | Male / Female |
| **Married** | Applicant marital status |
| **Dependents** | Number of dependents |
| **Education** | Graduate / Not Graduate |
| **Self_Employed** | Self-employed status |
| **ApplicantIncome** | Applicant’s monthly income |
| **CoapplicantIncome** | Co-applicant’s monthly income |
| **LoanAmount** | Loan amount (in thousands) |
| **Loan_Amount_Term** | Loan term (in months) |
| **Credit_History** | Credit history meets guidelines (1/0) |
| **Property_Area** | Urban / Semi-Urban / Rural |
| **Loan_Status** | Target variable (Y = Approved, N = Not Approved) |

---

## 🛠 Tech Stack

- **Programming Language:** Python 🐍  
- **Libraries Used:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Model:** Logistic Regression / Random Forest / XGBoost  
- **Deployment:** Streamlit / Flask  

---

## 📊 Exploratory Data Analysis (EDA)

- Handling missing values and categorical variables  
- Visualizing distributions of key features  
- Correlation heatmap to identify strong predictors  
- Outlier detection and feature scaling  

---

## 🤖 Model Training

1. **Data Splitting:** 80% Training, 20% Testing  
2. **Models Used:**  
   - Logistic Regression (Baseline)  
   - Random Forest Classifier  
   - XGBoost Classifier (Final Model)  
3. **Hyperparameter Tuning:** GridSearchCV / RandomizedSearchCV  
4. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC  

---

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|--------|-----------|------------|---------|-----------|
| Logistic Regression | 0.80 | 0.78 | 0.77 | 0.77 |
| Random Forest | 0.85 | 0.83 | 0.82 | 0.82 |
| XGBoost | 0.87 | 0.85 | 0.84 | 0.84 |

✅ **XGBoost Classifier** was chosen as the final model for deployment due to its superior performance.

---

## 🌐 Deployment

The project is deployed and accessible via [Live Demo](YOUR_DEPLOYMENT_LINK_HERE).  
You can input applicant details and instantly get the prediction for loan approval.

---

## 📂 Project Structure

