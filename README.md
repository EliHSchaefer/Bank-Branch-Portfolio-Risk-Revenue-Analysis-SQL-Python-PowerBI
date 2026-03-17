# Bank Branch Portfolio Risk & Revenue Analysis SQL-Python-PowerBI

## Overview
This project analyzes the financial performance of bank branches by combining **portfolio risk metrics, underwriting efficiency, revenue composition, and predictive modeling**. The goal is to understand **which branches generate the strongest risk-adjusted returns and why**.

Using **Python and Power BI**, the project builds a full analytics workflow:

- Data aggregation and feature engineering
- Portfolio concentration risk analysis
- Loan approval funnel analysis
- Revenue decomposition
- Risk-adjusted performance measurement
- Predictive modeling of branch performance
- Executive dashboard visualization

The final output is a **Power BI dashboard** and analytical framework for evaluating branch-level portfolio strategy.

---

# Key Questions

The analysis addresses several strategic questions:

1. Which branches generate the highest **risk-adjusted returns**?
2. How does **portfolio concentration risk** affect branch performance?
3. What role does **loan mix** (mortgage, auto, personal) play in revenue generation?
4. How efficient are branches at **converting loan applications into revenue**?
5. Which structural factors best explain differences in branch performance?

---

# Dataset

The project analyzes simulated banking transaction and loan data containing:

- Branch-level transactions
- Loan amounts and interest rates
- Loan approval / rejection outcomes
- Loan types (mortgage, auto, personal)
- Customer credit utilization
- Account balances and credit limits

From this raw dataset, branch-level metrics were engineered for analysis.

---

# Analytical Workflow

## 1. Portfolio Risk Analysis

Branch portfolio risk is evaluated using:

- **Herfindahl-Hirschman Index (HHI)**  
  Measures concentration of loan exposure.

- **Gini Coefficient**  
  Measures inequality in client revenue distribution.

- **Lorenz Curve**  
  Visualizes borrower concentration across branches.

These metrics identify branches with **high dependency on a small number of borrowers**.

---

## 2. Loan Approval Funnel

Branch underwriting performance is analyzed using a loan funnel:

