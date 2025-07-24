# VrindaStoreDataAnalysis
Sales analysis project using Excel to visualize and derive insights from Vrinda Store's 2022 data with an interactive dashboard.
<img width="1249" height="551" alt="Screenshot 2025-07-24 162241" src="https://github.com/user-attachments/assets/a2278df3-0865-4081-9fe8-601b931c4caa" />

# 🛒 Vrinda Store Analysis – Excel Project

## Overview  
This Excel project analyzes 2022 sales data for Vrinda Store to uncover insights into customer behavior and improve sales strategy. It uses Excel tools for data cleaning, pivot analysis, and dashboard visualization.

## 📁 Contents
- `Vrinda Store Data Analysis.xlsx` – Main workbook with multiple sheets:
  - **Raw Data** – Original dataset  
  - **Cleaned Data** – Cleaned and pre-processed version  
  - **Pivot Sheets** – Focused analysis:
    - Sales vs Orders  
    - Gender Breakdown  
    - Order Status  
    - Top 5 States  
    - Age vs Gender  
    - Sales Channels  
  - **Dashboard** – Interactive visual summary

## 🛠 Workflow

### 1. Data Cleaning  
- Standardized gender labels  
- Converted quantity values from text to numbers  
- Added columns for `Age Group` and `Month` using formulas like:
  - `=IF()` for categorizing age
  - `=TEXT(Date, "mmm")` for month extraction

### 2. Data Analysis with PivotTables  
Key pivot analyses include:
- **Monthly Sales vs Orders** (Combo chart)
- **Customer Gender Split** (Pie chart)
- **Order Status** breakdown
- **Top 5 Performing States**
- **Age × Gender Order Distribution**
- **Channel-wise Sales Contribution**

### 3. Dashboard  
An interactive dashboard was created using:
- PivotCharts and Slicers for filters  
- Clean layout with data storytelling focus  
- Charts formatted with labels, titles, and slicer interactivity

## 💡 Key Insights
- **March** recorded the highest sales and orders  
- **Women** made up over 60% of total customers  
- **Top states**: Maharashtra, Karnataka, Uttar Pradesh  
- **Age group 30–49** contributed the highest revenue  
- **Top sales channels**: Amazon, Flipkart, Myntra

## 🎯 Recommendations
- Focus marketing on **women aged 30–49** in top-performing states  
- Optimize presence on **Amazon, Flipkart, Myntra**  
- Launch seasonal campaigns around **March**


## 🧰 Tools & Techniques
- Microsoft Excel (Office 365)
- PivotTables & PivotCharts  
- Slicers for filtering  
- Formulas: `=IF()`, `=TEXT()`, conditional formatting  
- Chart types: Bar, Column, Pie, Combo

## 📌 Use Cases
- Academic portfolio project  
- Business analysis case study  
- Excel practice for data analysts  

## ✅ Contributing
Feel free to fork this repository and extend the analysis. Suggestions for:
- Category-level deep dives  
- Time series forecasting  
- Year-over-year comparisons  
are welcome.

## 📜 License
This project is licensed under the MIT License. See `LICENSE` file for details.



