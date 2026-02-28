# 💼 Job Salary Prediction using Machine Learning

## 📌 Overview
This project predicts the salary of a data science professional based on features like job title, experience level, company size, location, and work model.

The model is trained on a real-world dataset of data science salaries and uses regression techniques to estimate salary in USD.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Handle missing values and categorical encoding
- Train and compare multiple ML models
- Predict salaries based on input features
- Evaluate performance using MAE, RMSE, and R² Score

---

## 🗂️ Dataset Features
- job_title  
- experience_level  
- employment_type  
- work_models  
- work_year  
- employee_residence  
- salary  
- salary_currency  
- salary_in_usd  
- company_location  
- company_size  

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Google Colab

---

## 🔍 Exploratory Data Analysis
- Salary distribution across experience levels
- Salary trends over years
- Impact of company size and job roles
- Country-wise salary comparison

---

## 🤖 Models Used
| Model | MAE | RMSE | R² Score |
|------|------|------|---------|
| Linear Regression | 43566 | 63083 | 0.322 |
| Linear Regression (Log Target) | 41748 | 62982 | 0.325 |
| Random Forest | 44939 | 63909 | 0.305 |
| Random Forest (Log Target) | 43457 | 63530 | 0.313 |

---

## 📈 Final Model
The best performing model was:

👉 **Linear Regression with Log Transformation**

---

## 🧪 Example Prediction
**Input:**
- Experience Level: Senior
- Job Title: Data Scientist
- Company Size: Large
- Location: US

**Predicted Salary:** `$198,150`

---

## 🚀 How to Run This Project

1. Clone the repository
