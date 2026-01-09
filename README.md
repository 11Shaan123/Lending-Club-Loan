# Lending Club Case Study
# 📌 Project Overview
This project analyzes historical Lending Club loan data to understand the factors that influence whether a loan is **Fully Paid** or **Charged Off**. The analysis focuses on borrower characteristics, loan features, and risk indicators to support better loan approval and risk management decisions.

The work is primarily Exploratory Data Analysis (EDA) using Python and data visualization.

# ❓ Problem Statement
Loan default risk is one of the biggest challenges faced by financial institutions. Incorrect assessment can result in:

1.Significant financial losses

2.Poor portfolio performance

3.Increased charge-off rates

4.Reduced investor confidence

The challenge is to identify which borrower and loan characteristics are strongly associated with default risk, using historical data.

# 🎯 Project Objectives
1.Perform structured EDA on Lending Club loan data

2.Compare characteristics of Fully Paid vs Charged Off loans

3.Identify high-risk borrower and loan profiles

4.Understand the impact of:

A) Interest rate

B) Loan grade and sub-grade

C) Annual income

D) Loan amount

E) Employment length

5.Generate insights that can support credit policy and loan approval decisions

# 📊 Dataset Information

Source: Lending Club historical loan dataset

File Name: loan_csv.csv

Observations: Loan-level records for issued loans

Target Variable: loan_status

**Key Features Analyzed**

1.loan_amnt – Loan amount issued

2.int_rate – Interest rate of the loan

3.grade / sub_grade – Credit risk rating

4.annual_inc – Borrower’s annual income

5.emp_length – Employment length

6.term – Loan repayment term

7.loan_status – Outcome of the loan

# 🛠️ Tools & Technologies

Python 3 – Core programming language

Pandas – Data loading and manipulation

NumPy – Numerical computations

Matplotlib – Foundational visualizations

Seaborn – Statistical plotting

Jupyter Notebook – Interactive analysis environment

# 🔍 Analysis Approach

**1.Data Cleaning & Preparation**

A) Removed irrelevant columns

B) Handled missing and inconsistent values

C) Converted data types where necessary

D) Filtered dataset to focus on relevant loan statuses

**2.Univariate Analysis**

A) Distribution of Loan Amount

B) Total Number of Fully Paid vs Charged Off

C) Default Rate by Grade (Risk Profile)

D) Default Rate by Loan Term and Etc.

**3.Segmented Univariate Analysis**

A) Average Loan Amount by Grade

B) Loan Amount by Home Ownership

C) Monthly Installments by Loan Term'

D) Employment Length Count by Loan Status

**4.Bivariate Analysis**

A) Loan Amount Distribution across Grades

B) Verification Status vs Interest Rate

C) Default Percentage across Grades

D) DTI Ratio vs Loan Status

# 📊 Visualizations Used

Histograms and density plots

Box plots for distribution comparison

Bar charts for categorical variables

Count plots segmented by loan status and Many more

Each visualization is designed to clearly compare default vs non-default behavior.

# 📈 Key Insights & Findings

Loans with higher interest rates exhibit significantly higher default risk

Lower credit grades (D–G) show disproportionately higher charge-off rates

Borrowers with lower income brackets are more vulnerable to default

Employment length alone is not a strong predictor without considering other variables

Loan grade is one of the strongest indicators of loan outcome

# Acknowledgements

**This project was inspired by [Future Vision Classes](https://futurevisioncomputers.com/)**

# Collaborators

**Created By Shaan Panwala and Siddharth parekh**
