# Bank Loans Default Risk Analysis
## 1. Project Overview
###
Loan defaults represent a major source of financial loss for lending institutions.
This project analyzes historical consumer loan data to identify key drivers of default risk and translate analytical findings into actionable insights for credit risk management and lending decision support.

The analysis focuses on understanding how borrower characteristics, loan attributes, and repayment burden influence default behavior.

## 2. Business Objective
###
The primary objectives of this project are:

Identify key factors associated with loan default risk

Quantify how default rates vary across borrower and loan segments

Provide insights to support credit policy design and early risk monitoring

Establish a foundation for future credit scoring and predictive modeling

## 3. Dataset Overview
###
Number of records: 38,576 loans

Grain: One row represents one loan

Key data domains:

Loan characteristics: loan amount, term, interest rate, purpose

Borrower profile: income, employment length

Risk indicators: grade, sub-grade

Outcome variable: is_default

All analysis is based on historical, observational loan-level data.

## 4. Methodology
### The project follows a structured data analytics workflow:
### Data Cleaning & Preparation
####
Data type standardization

Handling missing and invalid values

Feature engineering (income bands, interest bands, loan age)
### Exploratory Data Analysis (EDA)
####
Segment-level default rate analysis

Identification of key risk drivers

Trend analysis across loan lifecycle
### Business Interpretation
####
Translation of statistical findings into credit risk insights

Validation of results through multiple segment comparisons
### Recommendations
####
Risk management implications

Credit policy considerations

Monitoring and early warning insights
## 5. Key Risk Drivers Identified
### 5.1 Repayment Burden

Loans with higher loan-to-income ratios exhibit significantly higher default rates, indicating that repayment burden is a primary determinant of credit risk.

### 5.2 Loan Purpose

Default rates vary substantially by loan purpose. Small business loans demonstrate the highest default rates, reflecting higher income volatility and business uncertainty compared to personal consumption loans.

### 5.3 Borrower Income

Default risk decreases consistently as borrower income increases, highlighting income stability as a protective factor. However, income alone does not fully mitigate risk when repayment burden is high.

### 5.4 Loan Maturity

Default events are heavily concentrated in the early stages of the loan lifecycle. Default rates decline sharply after the first two years, indicating that credit risk is front-loaded.

## 6. Supporting Evidence
###
Default rates more than double when loan amounts exceed approximately 30% of annual income

Small business loans exhibit default rates exceeding 25%, significantly higher than other loan purposes

Borrowers in the lowest income band default at rates above 17%, compared to approximately 10% for the highest income group

Loans older than two years show default rates below 5%, compared to over 20% in the first year

## 7. Recommendations
### 7.1 Risk Management

Loan-to-income ratio should be treated as a primary risk indicator. Borrowers whose loan size exceeds approximately 20–30% of annual income should be subject to stricter underwriting or risk-based pricing.

### 7.2 Credit Policy Implications

#### Loan Purpose Differentiation:
Small business loans may require enhanced documentation, tighter approval criteria, or higher pricing to compensate for elevated risk.

#### Income-Based Segmentation:
Credit assessment should emphasize relative repayment burden rather than absolute income levels.

### 7.3 Monitoring & Early Warning

Given that default risk is concentrated within the first 12–24 months, early-stage monitoring systems should be prioritized to detect early warning signals and mitigate losses.

## 8. Limitations
### 
The analysis is based on historical observational data and does not incorporate macroeconomic factors.

Loans classified as "Current" are treated as non-default, potentially underestimating future default risk.

Behavioral and payment history variables are not included.

## 9. Future Work
### 
Development of machine learning–based credit scoring models

Integration of macroeconomic indicators and behavioral data

Deployment of interactive dashboards for real-time risk monitoring

## 10. Tools & Technologies

### Python (Pandas, NumPy, Matplotlib, Seaborn)

### Power BI (Dashboard & Visualization)

### Git & GitHub (Version Control)

## 11. Summary
###
This project demonstrates how exploratory data analysis can be translated into actionable credit risk insights. By identifying repayment burden, loan purpose, borrower income, and loan maturity as key drivers of default, the analysis provides practical guidance for credit policy design, early risk monitoring, and future predictive modeling initiatives.
