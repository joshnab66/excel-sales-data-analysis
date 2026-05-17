# Sales Data Analysis Using Excel
### Kaggle Superstore Dataset — Data Cleaning, Formulas, Pivot Tables & Charts

---

## Project Overview

This project performs end-to-end sales data analysis on the Kaggle Superstore dataset using **Microsoft Excel (Google Sheets)**. It covers data cleaning, applying Excel formulas, building pivot tables, and creating charts to uncover real business insights from 9,800+ rows of sales data.

---

## Objectives

- ✅ Download a real-world dataset from Kaggle
- ✅ Clean the data — remove duplicates, fix formatting, handle missing values
- ✅ Apply Excel formulas — SUM, AVERAGE, IF, COUNTIF
- ✅ Create Pivot Tables — sales by region, category, and month
- ✅ Build Charts — Bar Chart and Line Chart
- ✅ Extract 3–4 meaningful business insights

---

## Files in This Repository

| File | Description |
|------|-------------|
| `Superstore_Raw_Data.xlsx` | Original dataset downloaded from Kaggle — no changes made |
| `Superstore_Cleaned_Analysis.xlsx` | Cleaned data with formulas, pivot tables, and charts |
| `README.md` | Project documentation |
| `screenshots/` | Screenshots of pivot tables and charts |

---

## Tools Used

- **Google Sheets** (exported as .xlsx)
- **Microsoft Excel** compatible format
- **Kaggle** — dataset source

---

## 🧹 Step 1 — Data Cleaning

Opened the raw CSV in Google Sheets and performed the following cleaning steps:

- **Removed duplicate rows** using Data → Remove Duplicates
- **Fixed 11 missing Postal Code values** — filtered blank cells and handled them
- **Standardized date format** — Order Date and Ship Date formatted to DD/MM/YYYY
- **Saved a separate cleaned file** — raw file was kept unchanged

---

## Step 2 — Formulas Applied

Created a dedicated **Formulas sheet** with the following:

| Formula | Purpose | Result |
|---------|---------|--------|
| `=SUM(Sales column)` | Total revenue across all orders | Overall sales figure |
| `=AVERAGE(Sales column)` | Average order value | Avg sale per transaction |
| `=COUNTIF(Category,"Technology")` | Count of Technology orders | Category frequency |
| `=COUNTIF(Category,"Furniture")` | Count of Furniture orders | Category frequency |
| `=COUNTIF(Category,"Office Supplies")` | Count of Office Supply orders | Category frequency |
| `=IF(Sales>500,"High Value","Low Value")` | Tag each order by size | New column added |

---

## Step 3 — Pivot Tables

### Pivot Table 1 — Sales by Region and Category
- **Rows:** Region (East, West, Central, South)
- **Columns:** Category (Furniture, Office Supplies, Technology)
- **Values:** SUM of Sales

| Region | Furniture | Office Supplies | Technology |
|--------|-----------|-----------------|------------|
| East | ✔ | ✔ | ✔ |
| West | ✔ | ✔ | ✔ |
| Central | ✔ | ✔ | ✔ |
| South | ✔ | ✔ | ✔ |

### Pivot Table 2 — Monthly Sales Trend
- **Rows:** Order Date (grouped by Month & Year)
- **Values:** SUM of Sales
- Shows how total sales changed month by month across all years

---

## Step 4 — Charts Created

### Chart 1 — Bar Chart
- **Title:** Sales by Region and Category
- **Source:** Pivot Table 1
- **Purpose:** Compare performance across all regions and product categories side by side
##  Step 5 — Key Insights Found

1. **West region leads in sales** — The West recorded the highest total revenue, followed by East, making them the two strongest performing regions.

2. **Technology is the top-earning category** — Despite having fewer orders than Office Supplies, Technology generated the highest sales value due to higher-priced items.

3. **Sales peak towards Q4 (Oct–Dec)** — The monthly trend shows a consistent spike near the end of each year, suggesting seasonal demand or holiday purchasing patterns.

4. **Furniture has low profit efficiency** — Furniture orders are large in value but often heavily discounted, meaning high sales numbers don't always translate to high profit.

---

## Sheet Structure

The Excel file contains the following sheets:

| Sheet Name | Contents |
|------------|----------|
| `Raw Data` | Original 9,800 rows of Superstore data |
| `Formulas` | SUM, AVERAGE, COUNTIF, IF results |
| `Pivot Analysis` | Region × Category pivot table + Bar Chart |
| `Monthly Trend` | Month-wise sales pivot table + Line Chart |

---

## 📥 Dataset Source

- **Name:** Sample Superstore Sales Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Rows:** 9,800
- **Columns:** 18 (Order ID, Region, Category, Sales, Ship Mode, Customer Name, etc.)

---

## Author

**Joshna Budha**  
B.Tech – Computer Science (AI & ML)  
Vignan's Institute of Engineering for Women, Visakhapatnam  
📧 buddhajoshna@mail.com  
🔗 [LinkedIn](https://linkedin.com/in/buddha-joshna-9b3b16341)

---

## Tags

`Excel` `Google Sheets` `Data Analysis` `Pivot Tables` `Data Cleaning` `VLOOKUP` `Data Visualization` `Kaggle` `Superstore` `Charts` `Business Intelligence`
