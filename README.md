# Loan Analysis – Financial Project (Excel + Power BI)

## Project Overview
This project focuses on analyzing financial loan data to understand borrower behavior, credit risk, and loan default patterns. The analysis was performed using **Excel for data preparation** and **Power BI for data modeling, DAX calculations, and dashboard creation**. The dataset contains over 45,000 loan records.

---

## Tools Used
- **Microsoft Excel** – Data cleaning, transformation, and calculated columns  
- **Power BI** – Data modeling, DAX measures, and interactive dashboards  

---

## Data Preparation (Excel)
The raw CSV file was loaded into Excel and converted into a structured table. The following steps were performed:

- Verified and standardized data types
   
- Checked for duplicates and missing values
    
- Created new calculated columns using **IF conditions** and ratio calculations
    
- Renamed columns for better clarity and business understanding  

The cleaned dataset was then imported into Power BI for further analysis.

---

## Power BI – DAX & Modeling
In Power BI, multiple DAX measures were created to support analysis, including metrics for total loans, approvals, defaults, default rate, high-risk loans, and average financial indicators. These measures were used across visuals and KPIs.

---

## Dashboards

### 🟢 Loan Overview Dashboard
**Purpose:** High-level summary of the loan portfolio.

**Includes:**
- KPI cards (Total Loans, Approved Loans, Default Loans, Default Rate)
  
- Loan distribution by loan intent
  
- Loan status overview
  
- Portfolio-level financial insights

**Key Insights:**
- A significant portion of loans fall under specific loan intents, indicating concentrated borrowing needs.
  
- Approval rates vary across loan categories, providing a clear view of overall portfolio health.

---
**Dashboard:**
<img width="1198" height="674" alt="image" src="https://github.com/user-attachments/assets/a1d1cc7e-adf1-4453-ba9a-624a4757c3c5" />


### 🔴 Risk & Customer Analysis Dashboard
**Purpose:** Analyze borrower risk and default behavior.

**Includes:**
- Credit score impact on default risk
  
- Default rate vs loan-to-income ratio
  
- High-risk loans by income range
  
- Employment stability vs loan status
  
- Credit history length vs default frequency
  
- Default rate by home ownership

**Key Insights:**
- Default risk decreases as credit score improves, highlighting credit score as a major risk factor.
  
- Higher loan-to-income ratios are associated with increased default probability.
  
- Borrowers with stable employment and longer credit history show lower default rates.

---
**Dashboard:**
<img width="1121" height="610" alt="image" src="https://github.com/user-attachments/assets/b17027fc-ebc6-4c81-8cbf-2eceb978f96d" />


## 🧠 Conclusion
This project demonstrates an end-to-end financial analytics workflow, combining Excel-based data preparation with Power BI modeling and visualization to derive meaningful insights into loan risk and customer behavior.
