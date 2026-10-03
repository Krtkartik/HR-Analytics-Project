IBM HR Analytics -- Employee Analysis

📌 Project Overview

This project focuses on analyzing the IBM HR Analytics Employee
Attrition dataset using Python. The project covers data preprocessing,
exploratory data analysis (EDA), feature preparation, machine learning,
and model evaluation.

The analysis mainly explores employee-related factors such as:

Age
Department
Job Role
Job Level
Monthly Income
Total Working Years
Years at Company
Job Satisfaction
Business Travel
Overtime
Attrition
Other employee and workplace attributes

The project was developed as a practical data analytics and machine
learning project using Python and Jupyter Notebook.

🎯 Objectives

Understand the structure and characteristics of the HR dataset.
Clean and prepare the data for analysis.
Explore employee and workplace patterns using EDA.
Identify relationships between employee attributes and
income/attrition.
Prepare categorical and numerical features for machine learning.
Build a Linear Regression model to predict Monthly Income.
Evaluate the model using standard regression metrics.
Identify useful HR insights from the analysis.

📊 Dataset

Dataset: IBM HR Analytics Employee Attrition Dataset
Rows: 1,470
Columns: 35
Data Types: Numerical and categorical
Target used in the implemented ML model: MonthlyIncome
The dataset contains employee information related to demographics, job
details, compensation, satisfaction, experience, and attrition.

🛠️ Technologies Used

Python
Jupyter Notebook
Pandas -- data loading and manipulation
NumPy -- numerical operations
Matplotlib -- data visualization
Seaborn -- statistical visualization
Scikit-learn -- preprocessing, train-test split and Linear
Regression

🔄 Project Workflow

1. Data Import & Inspection
The dataset was loaded into Python and examined to understand:
Dataset shape
Column names
Data types
Missing values
Duplicate records
Basic statistics

2. Data Cleaning & Preprocessing
The preprocessing stage included:
Checking for missing values.
Checking duplicate records.
Removing constant/unnecessary columns.
Identifying potential outliers.
Preparing numerical and categorical variables for further analysis.
The constant columns identified in the dataset included:
EmployeeCount
Over18
StandardHours

These columns do not provide useful variation for analysis and were
removed.

3. Exploratory Data Analysis
Different visualizations were used to understand the dataset, including:
Histograms
Bar charts
Box plots
Attrition distribution plots
Correlation heatmap
Department-wise analysis
Job Role analysis
Gender-wise analysis
Overtime vs Attrition analysis

4. Feature Engineering
Categorical variables were converted into numerical form so that they
could be used by the machine learning model.
Numerical features were also prepared/scaled where required.

5. Model Building

A Linear Regression model was implemented.
Target variable: MonthlyIncome
Training data: 80%
Testing data: 20%
The model uses employee-related features to estimate their Monthly
Income.

6. Model Evaluation

The model was evaluated using:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
R² Score
Additional plots were used to understand:
Actual vs Predicted values
Prediction errors/residuals
Feature coefficients

🔍 Key Findings

The EDA showed several useful relationships in the dataset:
Monthly Income has a positive relationship with Job Level.
Total Working Years is positively related to Monthly Income.
Employees with greater experience generally tend to have higher
income.
Employees with lower income and fewer years at the company show
higher levels of attrition in the analysis.
Overtime, job role, department, and other employee-related factors
show differences in attrition patterns.
These findings help demonstrate how HR data can be used to understand
employee and compensation patterns.

📈 Model Interpretation

The Linear Regression model provides an estimate of Monthly Income based
on the available employee features.
The project also includes coefficient analysis to understand how
different features contribute to the predicted income.

For example, Job Level shows a strong relationship with Monthly
Income, which is consistent with the salary patterns observed during
EDA.

📁 Project Structure

IBM-HR-Analytics/
│
├── HR_Analytic_Project.ipynb
├── IBM HR Analytics Report.docx
├── Minor Project.pdf
├── README.md
└── dataset/
    └── WA_Fn-UseC_-HR-Employee-Attrition.csv


📌 Important Note About the ML Objective

The assigned project title is "IBM HR Analytics - Employee Attrition
Analysis", and the assignment asks for a machine learning model to
predict employee attrition.

However, the implemented notebook/report currently uses Linear
Regression to predict MonthlyIncome, not an Attrition classification
model.

Therefore:

The HR analysis and EDA cover attrition-related patterns.
The implemented ML model is a regression model for Monthly
Income.

A separate classification model for Attrition would be
required if the project needs to match the assignment's ML objective
exactly.

🔮 Future Improvements

The project can be extended by:

Building classification models for employee attrition.

Comparing Logistic Regression, Decision Tree, and Random Forest.

Using accuracy, precision, recall, and F1-score for classification.

Applying cross-validation.

Performing more detailed feature engineering.

Testing advanced models such as Random Forest, Gradient Boosting, or
XGBoost.

Creating an interactive HR analytics dashboard.

📝 Conclusion

This project demonstrates a complete practical workflow for working with
HR data --- from data cleaning and exploratory analysis to feature
preparation, machine learning, and model evaluation.

The analysis highlights relationships between income, experience, job
level, and employee attrition, while the implemented Linear Regression
model demonstrates how employee attributes can be used to estimate
Monthly Income.

The project also provides a foundation for extending the analysis into a
dedicated employee attrition prediction system.

