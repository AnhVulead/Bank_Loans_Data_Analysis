# 🏦 Bank Loans Default Risk Analysis

## 📌 Project Overview
Loan defaults are a major source of financial loss for lending institutions.  
This project analyzes historical consumer loan data to identify **key drivers of default risk** and translate analytical findings into **actionable credit risk insights**.

The analysis focuses on how **borrower characteristics**, **loan attributes**, and **repayment burden** influence default behavior, supporting data-driven lending and risk management decisions.

---

## 🎯 Business Objectives
- Identify key factors associated with loan default risk
- Quantify default rate variation across borrower and loan segments
- Support credit policy design and early risk monitoring
- Establish a foundation for future credit scoring and predictive modeling

---

## 📂 Dataset Overview
- **Number of records:** 38,576 loans  
- **Grain:** One row per loan  

### Key Data Domains
- **Loan attributes:** loan amount, term, interest rate, purpose  
- **Borrower profile:** annual income, employment length  
- **Risk indicators:** credit grade, sub-grade  
- **Outcome variable:** `is_default`

All analysis is based on historical, observational loan-level data.

---

## 🧠 Methodology

### 1. Data Cleaning & Preparation
- Data type standardization
- Handling missing and invalid values
- Feature engineering:
  - Income bands
  - Loan-to-income ratio
  - Loan age bands

### 2. Exploratory Data Analysis (EDA)
- Segment-level default rate analysis
- Identification of major risk drivers
- Default trends across the loan lifecycle

### 3. Business Interpretation
- Translation of statistical patterns into credit risk insights
- Cross-validation through multiple segment comparisons

### 4. Recommendations
- Risk management implications
- Credit policy considerations
- Early warning and monitoring insights

---

## 🔍 Key Risk Drivers Identified

### Repayment Burden
Loans with higher **loan-to-income ratios** show significantly higher default rates, making repayment burden a primary determinant of credit risk.

### Loan Purpose
Default rates vary substantially by loan purpose.  
**Small business loans** exhibit the highest default rates, reflecting income volatility and operational uncertainty.

### Borrower Income
Default risk decreases as income increases, indicating income stability as a protective factor.  
However, high income does not fully offset excessive repayment burden.

### Loan Maturity
Defaults are heavily **front-loaded**:
- Highest risk in the first 12–24 months
- Default rates decline sharply after two years

---

## 📊 Supporting Evidence
- Default rates more than **double** when loan size exceeds ~30% of annual income
- Small business loans show default rates **above 25%**
- Lowest income group defaults at **>17%**, compared to ~10% for highest income group
- Loans older than two years show default rates **below 5%**

---

## 🧩 Recommendations

### Risk Management
- Treat **loan-to-income ratio** as a primary risk indicator
- Apply stricter underwriting or risk-based pricing for loans exceeding 20–30% of annual income

### Credit Policy Implications
**Loan Purpose Differentiation**
- Small business loans require tighter approval criteria or higher pricing

**Income-Based Segmentation**
- Focus on **relative repayment burden**, not absolute income alone

### Monitoring & Early Warning
- Prioritize monitoring during the first **12–24 months**, where default risk is highest

---

## ⚠️ Limitations
- No macroeconomic variables included
- Current loans treated as non-default (potential underestimation)
- Lack of behavioral and payment history features

---

## 🚀 Future Work
- Machine learning–based credit scoring models
- Integration of macroeconomic and behavioral data
- Deployment of interactive dashboards for real-time monitoring

---

## 🛠 Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Power BI:** Dashboard & visualization  
- **Git & GitHub:** Version control  

---

## 📌 Summary
This project demonstrates how exploratory data analysis can be transformed into **practical credit risk insights**.  
By identifying repayment burden, loan purpose, borrower income, and loan maturity as key default drivers, the analysis supports more effective credit policy design, early risk detection, and future predictive modeling initiatives.
