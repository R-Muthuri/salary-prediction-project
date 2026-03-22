# Job Salary Prediction & Analysis

## Overview
This project develops a machine learning model to predict job salaries using features such as job title, experience, education level, skills, certifications, and industry factors.

The analysis combines exploratory data analysis (EDA), correlation analysis, and regression modeling to identify key drivers of salary and evaluate predictive performance.

---

## Objectives
- Understand factors influencing salary
- Analyze relationships between experience, skills, and salary
- Build a predictive model using machine learning
- Compare model performance with and without job title

---

## Dataset
The dataset contains 250,000 records with the following features:
- job_title
- experience_years
- education_level
- skills_count
- industry
- company_size
- location
- remote_work
- certifications
- salary

---

## Key Insights

- Experience has a moderate positive relationship with salary (≈ 0.44)
- Skills and certifications have weak relationships (≈ 0.13 and 0.07)
- Job title explains ~16% of salary variation independently
- Salary is influenced by multiple interacting factors

---

## Model Performance

| Model | Description | R² Score |
|------|------------|--------|
| Full Model | Includes job_title (OneHotEncoder) | 0.96 |
| Reduced Model | Excludes job_title | 0.80 |
| Ordinal Model | Uses OrdinalEncoder | 0.45 |

---

## Key Findings

- Job role significantly improves predictive accuracy
- Experience is the strongest individual predictor
- Salary is multi-factor driven, not dependent on a single variable
- OneHotEncoding outperforms OrdinalEncoding for categorical data

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Conclusion

Salary is determined by a combination of structural factors (job role) and individual attributes (experience, education, and skills). While job title enhances prediction accuracy, experience remains the most important individual driver of salary.

---

## Author
Raphael Muthuri
