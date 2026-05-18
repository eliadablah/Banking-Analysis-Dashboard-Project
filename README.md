# 🏦 Banking Dashboard - End-to-End Data Analysis Project

This project focuses on building an interactive **Banking Dashboard** using Power BI. It involves the complete data analysis lifecycle — from data cleaning and transformation to exploratory data analysis (EDA) and visualization.

---

## 📌 Project Workflow

Data ➡️ MySQL ➡️ Data Cleaning & Preparation ➡️ EDA ➡️ Power BI Dashboard

---

## 📊 Dataset Information

- **Number of columns**: 24
- **Stored in**: MySQL

---

## 🔧 Steps Involved

### 1. Data Cleaning & Preparation

- Categorized `Income` into bands:
  - `Low`
  - `Mid`
  - `High`
- Standardized gender, nationality, and other categorical variables.
- Used conditional columns in Power BI to create income bands.
- Replaced branch codes (`'1'`, `'2'`, etc.) with readable branch names.
- Mapped gender codes:
  - `'1'` → `Male`
  - `'2'` → `Female`

---

### 2. Exploratory Data Analysis (EDA)

- Categorical analysis on:
  - Gender
  - Nationality
- Numerical analysis on:
  - Credit Card Balance
  - Bank Loans
  - Bank Deposits
  - Checking Account
  - Saving Account
  - Estimated Income
  - Superannuation Savings

---

### 3. Key Insights from EDA

- Strong positive correlation between:
  - `Bank Deposits`, `Checking Account`, `Saving Account`, and `Foreign Currency Account`.
- Customers with high balance in one account type tend to hold substantial funds in other accounts as well.

---

## 📈 Dashboard Pages (Power BI)

1. **Home**
2. **Loan Analysis**
3. **Deposit Analysis**
4. **Summary**

---

## 🚀 Tools & Technologies

- **Database**: MySQL
- **Visualization**: Power BI
- **Languages**: SQL, DAX (in Power BI)

---

## 🧠 Learnings

- Data wrangling using SQL
- Power BI conditional columns
- Deriving insights through EDA
- Building multi-page dashboards for presentation

---
### ✅ Page 1: Home  
> Overview of the banking data with summary statistics and key visuals.  

<img src="powerbi/page1_home.png" alt="Page 1 - Home" width="700"/>

---

### ✅ Page 2: Loan Analysis  
> Insights into loan distribution, types, and customer segments.  

<img src="powerbi/page2_loan_analysis.png" alt="Page 2 - Loan Analysis" width="700"/>

---

### ✅ Page 3: Deposit Analysis  
> Breakdown of account balances, deposit types, and correlation patterns.  

<img src="powerbi/page3_deposit_analysis.png" alt="Page 3 - Deposit Analysis" width="700"/>

---

### ✅ Page 4: Summary  
> Final insights from EDA, including correlations and demographic trends.  

<img src="powerbi/page4_summary.png" alt="Page 4 - Summary" width="700"/>

<img width="1304" height="732" alt="page1_home" src="https://github.com/user-attachments/assets/ab67052a-af55-4dcd-857c-2deef7a931e6" />
<img width="1305" height="732" alt="page2_loan_analysis" src="https://github.com/user-attachments/assets/739511ed-1349-4574-9380-0e98e7c9ed6e" />
<img width="1306" height="733" alt="page3_deposit_analysis" src="https://github.com/user-attachments/assets/2f59e935-5e6b-4bd7-9660-3395a2315e68" />
<img width="1306" height="735" alt="page4_summary" src="https://github.com/user-attachments/assets/d4457683-3f67-49c6-8693-564633b7797c" />

