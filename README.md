![image](https://github.com/user-attachments/assets/7189aa5c-2353-40e8-8608-6b275eef5b14)# Bank Loan Report

## Project Overview  
This project provides an in-depth analysis of bank loan data, focusing on borrower characteristics, loan statuses, and associated risks. The analysis aims to assist banks in making informed decisions, managing risk, and optimizing loan portfolios.

---

## Problem Statement  
Banking institutions face challenges in assessing loan risk, managing portfolios, and ensuring regulatory compliance. By analyzing the dataset, this project provides insights into:
- Borrower creditworthiness.
- Loan performance trends.
- Risk management strategies.

---

## Domain Knowledge  
Bank loans are critical financial tools that enable individuals and businesses to manage financial needs and achieve goals. However, the complexity of assessing and managing loans requires in-depth data analysis. 

### Key Aspects:
1. **Data Sources**:
   - Loan Applications.
   - Credit Reports.
   - Internal Records.
   - Online Portals.
   - Third-party Data.

2. **Process of Granting a Loan**:
   - Loan Application Submission.
   - Identity and Credit Verification.
   - Income and Employment Assessment.
   - Risk Evaluation and Loan Approval.

3. **Reasons for Analyzing Loan Data**:
   - Risk Assessment.
   - Fraud Detection.
   - Portfolio and Credit Risk Management.
   - Regulatory Compliance.
   - Customer Insights.

---

## Technologies Used  
- **Languages**: SQL.  
- **Tools**: Tableau.  
- **Database Management**: MySQL.  

---

## Dataset  
The dataset contains details of bank loans, including borrower demographics, loan characteristics, and repayment statuses. The dataset was utilized to perform SQL queries for analyzing loan trends, borrower behaviors, and loan performance.

[Download the Dataset](data/bank_loan_data.csv)

---

## Query Document  
The query document contains SQL code and results for various analyses performed on the dataset, such as:
- Loan status distribution.
- Average interest rates by risk grade.
- Borrower characteristics affecting loan approval.

[Download the Query Document](queries/loan_queries.sql)

---

## Terminologies Used in Data  
### Fields and Their Use in Banking  
- **Loan ID**: Unique identifier for loans.  
- **Address State**: Borrower's location.  
- **Employee Length**: Borrower's employment stability.  
- **Grade & Sub-Grade**: Credit risk classifications.  
- **Home Ownership**: Housing status of borrowers.  
- **Annual Income**: Borrower’s earnings to assess repayment capacity.  
- **DTI (Debt-to-Income Ratio)**: Debt burden relative to income.  
- **Loan Amount**: Principal amount borrowed.  
- **Interest Rate**: Annual cost of borrowing.

For a detailed explanation, refer to the project documentation.

---

## Dashboard Overview

The project includes three key dashboards: **Summary**, **Overview**, and **Detail**. These dashboards help users understand different aspects of loan data, including general trends, detailed analyses, and summary statistics.  
**Note**: All dashboards were built using a **self-created background** for a customized look and feel.

### 1. Summary Dashboard  
This dashboard provides a high-level view of the loan data, showcasing the key performance indicators such as loan amounts, interest rates, and borrower characteristics in an aggregated form.

![Summary Dashboard](images/Summary.png)

### 2. Overview Dashboard  
The Overview dashboard offers insights into the loan statuses, risk classifications, and borrower distributions, helping users get an overview of the loan portfolio’s health.

![Overview Dashboard](images/Overview.png)

### 3. Detail Dashboard  
This dashboard provides a deep dive into the data, offering detailed insights into individual loan records, repayment statuses, and borrower-specific trends.

![Detail Dashboard](images/Details.png)

---

## Insights and Conclusion  
By analyzing the data:
- Banks can improve risk assessment models.
- Tailored loan products can be designed for different borrower segments.
- Trends in loan performance can guide better decision-making.

---

## How to Run the Project

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/bank-loan-report.git
