# Employee Attrition Prediction

A Machine Learning project that predicts whether an employee is likely to leave the company using HR analytics data. The project includes data preprocessing, exploratory data analysis (EDA), model comparison, feature importance analysis, and actionable HR insights.

---

## 📌 Overview

Employee attrition impacts an organization's productivity, hiring costs, and employee morale. This project leverages machine learning to identify employees at risk of leaving, enabling HR teams to take proactive retention measures.

---

## Dataset

- **Dataset:** IBM HR Analytics Employee Attrition
- **Total Employees:** 1,470
- **Target Variable:** `Attrition`
  - `0` → Employee Stayed
  - `1` → Employee Left

---

## Features

- Data Cleaning & Preprocessing
- Missing Value Analysis
- Exploratory Data Analysis (EDA)
- One-Hot Encoding
- Feature Scaling
- Model Training & Comparison
- Feature Importance Analysis
- Business Insights & HR Recommendations

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## Model Evaluation

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|--------|----------|-----------|--------|----------|---------|
| Logistic Regression | 0.752 | 0.349 | 0.638 | 0.451 | 0.803 |
| Random Forest | 0.844 | 0.571 | 0.085 | 0.148 | 0.769 |
| Gradient Boosting | 0.857 | 0.667 | 0.213 | 0.323 | 0.804 |

---

## Exploratory Data Analysis

Key findings from the analysis:

- Overall employee attrition rate is **16.12%**
- Sales has the highest attrition rate.
- Employees with lower monthly income are more likely to leave.
- Employees working overtime have a higher chance of attrition.
- Most employees leave during their early years at the company.

---

## Top Factors Influencing Attrition

- Monthly Income
- OverTime
- Age
- Total Working Years
- Years at Company
- Job Level
- Distance From Home
- Stock Option Level
- Job Involvement
- Work-Life Balance

---

## Visualizations

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income vs Attrition
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison

---

## Business Recommendations

- Improve work-life balance by reducing excessive overtime.
- Focus retention efforts on employees in the Sales department and high-risk job roles.
- Conduct regular career development discussions for employees in their first few years.
- Review compensation and growth opportunities for employees at higher risk of leaving.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- SMOTE for handling class imbalance
- Model deployment using Streamlit
- Explainable AI using SHAP

---

## 👩‍💻 Author

**Sneha**

Computer Science Undergraduate | AI & Machine Learning Enthusiast
