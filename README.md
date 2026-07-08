# Employee Salary Prediction

## Project Overview

This project aims to predict employee salaries using Machine Learning regression models. The model estimates salary based on employee characteristics such as job title, experience, education level, company size, industry, location, certifications, and technical skills.

The project follows a complete Machine Learning workflow from data preprocessing to model evaluation.

---

## Business Problem

Accurate salary prediction helps companies:

- Build fair compensation systems.
- Benchmark salaries across industries.
- Improve hiring decisions.
- Support HR analytics and workforce planning.

---

## Dataset

The dataset contains **250,000 employee records** with the following features:

- Job Title
- Experience Years
- Education Level
- Skills Count
- Industry
- Company Size
- Location
- Remote Work
- Certifications

Target Variable:

- Salary

---

## Machine Learning Workflow

- Business Understanding
- Data Understanding
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Encoding
- Feature Scaling
- Train/Test Split
- Baseline Models
- Model Comparison
- Final Model Selection
- Model Evaluation
- Feature Importance
- Business Insights

---

## Feature Engineering

A new feature was created:

- **experience_per_skill**

```
experience_years / skills_count
```

This feature represents the average years of experience per skill.

---

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## Model Performance

| Model | MAE | RMSE | R² |
|-------|------:|------:|------:|
| Linear Regression | 5436.09 | 7125.50 | **0.9635** |
| Decision Tree | 8060.92 | 10562.79 | 0.9197 |
| Random Forest | 5778.73 | 7498.15 | 0.9595 |

**Best Model:** Linear Regression

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Joblib

---

## Repository Structure

```
Employee-Salary-Prediction/
│
├── Employee_Salary_prediction.ipynb
├── employee_salary_prediction_model.pkl
├── scaler.pkl
├── job_salary_prediction_dataset.csv
└── README.md
```

---

