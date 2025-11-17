📊 Loan Approval Analysis – Exploratory Data Analysis (EDA)

This project performs a complete Exploratory Data Analysis (EDA) on a Home Loan Approval dataset.
The analysis uncovers key financial and demographic factors that influence loan approval decisions and provides insights that lenders can use to improve risk assessment.

🚀 Project Overview

This project aims to:

Explore applicant details such as income, education, employment, and property area

Analyze loan amount patterns and approval trends

Examine relationships between numeric and categorical features

Identify important insights through visualizations

Understand the factors that strongly influence loan approval

This EDA serves as a foundation for risk modeling, credit scoring, or machine-learning tasks.

📁 Dataset Information

Total Records: 614

Total Features: 13

Numeric Columns:

ApplicantIncome

CoapplicantIncome

LoanAmount

Categorical Columns:
Gender, Married, Education, Self_Employed, Credit_History, Property_Area, Loan_Status

The dataset includes demographic, financial, and loan-related attributes.

🧹 Data Cleaning Steps

Filled missing values

Categorical → Mode

Numeric → Mean

Dropped Loan_ID as it does not contribute analytically

Verified dataset for duplicates

Ensured all missing values were resolved

📊 Exploratory Data Analysis (EDA)
Univariate Analysis

Income distribution

Loan amount distribution

Outlier detection

Categorical frequency analysis

Bivariate Analysis

Applicant income vs loan amount

Co-applicant income vs loan amount

Numeric vs categorical analysis using boxplots

Multivariate Analysis

Correlation heatmap

Pair plot of numeric features

Combined demographic & financial patterns

⭐ Key Insights From the Analysis

High-income applicants earn up to ₹1.3M more than others.

Average approved loan ≈ ₹146K, which is about 38% of average monthly income.

Graduates have +17% higher loan approval rate than non-graduates.

Urban property owners receive ₹40K higher loan amounts on average.

Credit history is the most dominant factor influencing approval.

Applicant income and co-applicant income together show strong combined impact on loan amount.

🛠️ Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Jupyter Notebook
