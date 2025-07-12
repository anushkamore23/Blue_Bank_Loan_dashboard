# 🏦 Blue Bank Loan Dashboard

A business intelligence dashboard built with **Python** and **Tableau** to help Blue Bank understand the financial risk associated with loan applicants.
View Dashbord (https://public.tableau.com/app/profile/anushka.more8758/viz/BlueBankLoanAnalysis_17413666179240/Dashboard1)

## 📌 Project Overview

Blue Bank, a U.S.-based financial institution, faced challenges due to a lack of reporting on borrower risk. With limited staff in the loan department, they needed an automated solution to analyze borrower profiles and flag potential risks.

This dashboard provides a **comprehensive overview** of:
- Credit utilization,
- Debt-to-income ratio,
- FICO scores,
- Loan distribution by income,
- and more.

---

## 🎯 Goals

- Visualize loan distribution across key metrics.
- Help staff identify **risky borrowers** using credit utilization and FICO score analysis.
- Enable quick filtering by income group and interest rate types.
- Deliver an **interactive dashboard** with dynamic filters using Tableau.

---

## 🧩 Data Source

- File Format: `.csv` 
- Fields: `Interest Rate`, `FICO Score`, `Debt-to-Income Ratio`, `Utilization Rate`, `Annual Income`, etc.
- Data cleaning and transformation was done using Python.

🔗 Python script available here:  
[`blue_bank_loan.py`](https://github.com/anushkamore23/Python-Tableau/blob/main/Blue_bank_loan.py)

---

## 📊 Dashboard Highlights

| Component                                | Description                                                         |
|------------------------------------------|---------------------------------------------------------------------|
| **Filters**                              | Interest Rate Type, FICO Category, and Income Group filters         |
| **KPI Tiles**                            | Avg Debt-to-Income, Max Revolving Balance, Min Interest Rate        |
| **Pie Chart: Loans by Interest Rate**    | Breakdown of high vs. low interest loans                            |
| **Bar Chart: Utilization Rate**          | Shows how many loans fall into credit usage bins                    |
| **Bar Chart: Loans by FICO Score**       | Creditworthiness of borrowers (Excellent, Good, Fair)               |
| **Bar Chart: Loans by Income Group**     | Helps segment loans by annual income                               |

---

## 💡 Key Insights

- Most borrowers fall under **Excellent and Good FICO categories**.
- High-interest loans (~45%) may indicate **higher-risk** profiles.
- Borrowers with **50–100% utilization rates** are more common and might need review.
- Majority of loans come from the **middle-income group ($10k–$100k)**.

---

## 🛠 Tech Stack

| Tool        | Purpose                                  |
|-------------|------------------------------------------|
| **Python**  | Data cleaning and preprocessing          |
| **Pandas**  | Data manipulation                        |
| **Tableau** | Visualization and dashboard development  |
| **Excel/CSV** | Original data source                   |

---



