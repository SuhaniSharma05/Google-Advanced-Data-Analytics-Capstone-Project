# Employee Turnover Prediction
This project predicts whether an employee is likely to leave the company using machine learning models. It also identifies the key factors that influence employee attrition based on HR data.
# Objective
- Predict employee turnover
- Analyze factors influencing attrition
- Help HR make data-driven decisions
# Dataset
- Source: [Kaggle HR Dataset](https://www.kaggle.com/datasets)
- Features: satisfaction_level, last_evaluation, number_of_projects, average_monthly_hours, time_spent_company, salary, department
- Target: left (1 = left company, 0 = stayed)
# Tools and Libraries
- Python, Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Logistic Regression, Random Forest, XGBoost)
# Project Workflow
1. Load and clean the data
2. Perform Exploratory Data Analysis (EDA)
3. Encode categorical variables and normalize data
4. Train models and evaluate performance
5. Interpret model results and feature importance
# Key Findings
- Low satisfaction is the strongest predictor of leaving
- High working hours and lack of promotions contribute to turnover
- Low salary correlates with high attrition
- Random Forest gave best results (~88% accuracy)
