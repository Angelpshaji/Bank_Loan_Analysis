# 📊 Bank Loan Data Analysis Project

This project focuses on analyzing a **Bank Loan Dataset** using Python to uncover insights related to loan performance, customer behavior, and financial trends. The analysis includes exploratory data analysis (EDA), loan classification (Good vs Bad Loans), visualizations, and KPI calculations.

---

## ✅ Project Objectives

✔ Understand overall loan performance  
✔ Identify Good vs Bad Loans based on loan status  
✔ Analyze funding trends and repayment patterns  
✔ Perform regional, term-wise, and home-ownership-based analysis  
✔ Visualize insights using Python libraries  

---

## 🛠️ Tools & Libraries Used

| Library     | Purpose |
|-------------|------------------------------------------------|
| **Pandas**  | Data cleaning, transformation, aggregation     |
| **NumPy**   | Numerical operations, handling missing values  |
| **Matplotlib** | Static visualizations (bar, line, pie charts) |
| **Seaborn** | Enhanced statistical visualizations            |
| **Plotly**  | Interactive charts like Treemap, Donut charts  |
| **Datetime (.dt)** | Date-based filtering (MTD, YTD analysis) |

---

## 📁 Dataset Overview

| Feature Name     | Description |
|------------------|-------------|
| `loan_amount`    | Total amount funded by the bank |
| `total_payment`  | Amount received from the customer |
| `loan_status`    | Current status of the loan (Fully Paid/Charged Off) |
| `issue_date`     | Loan issue date |
| `term`           | Loan term (36 or 60 months) |
| `address_state`  | State of loan holder |
| `home_ownership` | Home ownership status (Rent, Own, Mortgage) |
| `int_rate`       | Interest rate of the loan |
| `dti`            | Debt-to-Income ratio |

---

## 📌 Key Insights & Analysis Performed

### ✅ 1. **Good Loan vs Bad Loan Analysis**
- Filtered loans using `loan_status`
- Calculated:
  - Total Applications  
  - Funded Amount  
  - Amount Received  
  - Recovery Percentage  

### ✅ 2. **Month-to-Date (MTD) & Yearly Analysis**
- Used `.dt.year` and `.dt.month`  
- Calculated:
  - MTD Funded Amount  
  - MTD Amount Received  

### ✅ 3. **Regional (State-wise) Analysis**
- Grouped loan amounts and payments by `address_state`
- Visualized using horizontal bar charts

### ✅ 4. **Loan Term Analysis**
- Compared 36-month vs 60-month loans
- Created Donut Pie Charts for:
  - Total Funded Amount  
  - Total Amount Received  
  - Loan Applications  

### ✅ 5. **Home Ownership Analysis**
- Treemap showing funded amount by home ownership using Plotly

---

## 📊 Sample Visualizations

- ✅ Good vs Bad Loan Comparison  
- ✅ Monthly Funding & Repayment Trends  
- ✅ State-wise Funded Amount (Bar Chart)  
- ✅ Loan Term-wise Donut Charts (36M vs 60M)  
- ✅ Treemap: Home Ownership vs Funded Amount  

---
