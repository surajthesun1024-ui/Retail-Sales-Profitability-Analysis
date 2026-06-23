# Retail-Sales-Analysis

## Project Overview

This project analyzes retail sales data to uncover key revenue drivers, profitability trends, customer segment performance, regional performance, and the impact of discounting on overall business profitability.

The analysis was conducted using Python for data cleaning, feature engineering, and exploratory data analysis (EDA), followed by Power BI for interactive dashboard development and business reporting.

---

## Business Objective

The primary objective of this project is to:

* Identify the most profitable product categories and sub-categories.
* Analyze customer segment performance.
* Evaluate regional profitability.
* Understand the impact of discounts on profit and profit margins.
* Detect loss-making products and business areas requiring attention.

---

## Dataset Information

The dataset contains retail transaction records including:

* Order Details
* Sales
* Profit
* Discount
* Quantity
* Category
* Sub-Category
* Customer Segment
* Region
* State
* Ship Mode

---

## Tools & Technologies

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

### Business Intelligence

* Power BI
* DAX Measures

### Version Control

* Git
* GitHub

---

## Project Workflow

### 1. Data Cleaning

* Checked missing values
* Verified data types
* Removed duplicate records
* Validated dataset consistency

### 2. Feature Engineering

Created additional business-focused features:

#### Profit Margin

Profit Margin = Profit / Sales

#### Discount Category

* No Discount
* Low Discount
* Medium Discount
* High Discount

#### Loss Flag

* Profit
* Loss

### 3. Exploratory Data Analysis

Performed:

* Univariate Analysis
* Category Analysis
* Sub-Category Analysis
* Segment Analysis
* Regional Analysis
* Discount Analysis
* Profitability Analysis

### 4. Dashboard Development

Built an interactive Power BI dashboard consisting of three analytical pages:

* Executive Summary
* Profitability Analysis
* Discount & Loss Analysis

---

# Key Insights

### Overall Business Performance

* Total Sales reached **$2.30 Million**.
* Total Profit generated was **$286.24 Thousand**.
* The business processed approximately **10,000 orders**.
* Overall Profit Margin stood at **12.47%**.
* Average Discount across all transactions was **15.63%**.

### Sales Performance

* Technology generated the highest sales of approximately **$0.84 Million**.
* Furniture generated sales of approximately **$0.74 Million**.
* Office Supplies generated sales of approximately **$0.72 Million**.
* Consumer customers contributed over **50.5% of total sales**, making them the largest customer segment.

### Profitability Analysis

* Technology generated the highest profit of approximately **$145K**.
* Office Supplies generated approximately **$122K** profit.
* Furniture generated only **$18K** profit despite strong sales volume.
* Copiers (**$56K**) and Phones (**$45K**) were the most profitable sub-categories.
* The West region generated the highest profit of approximately **$108K**, followed by East (**$92K**).

### Discount & Loss Analysis

* Orders without discounts generated approximately **$320K** profit.
* High-discount transactions generated overall losses of approximately **$90K**.
* Profit margins declined sharply as discount levels increased, becoming strongly negative for high-discount transactions.
* Approximately **81.27%** of transactions were profitable, while **18.73%** resulted in losses.

### Loss-Making Areas

* Tables were the largest loss-making sub-category, generating losses of approximately **$18K**.
* Bookcases generated losses of approximately **$4K**.
* Supplies generated losses of approximately **$1K**.
* Binders, Machines, Tables, and Bookcases received the highest average discounts, contributing significantly to profitability erosion.
---

# Business Recommendations

### 1. Optimize Discount Strategy

High-discount transactions generated approximately **$90K in losses** and significantly reduced profit margins. Discount policies should be reviewed and controlled.

### 2. Address Loss-Making Products

Tables, Bookcases, and Supplies consistently generated losses despite contributing to sales volume. Pricing and promotional strategies should be reassessed.

### 3. Prioritize Technology Products

Technology generated the highest sales (**$0.84M**) and profit (**$145K**), making it the strongest category for future growth initiatives.

### 4. Focus on Consumer Customers

Consumer customers contributed more than **50% of total sales**, indicating a strong opportunity for customer retention and targeted marketing.

### 5. Replicate Regional Success

The West region generated the highest profit (**$108K**). Successful practices from this region can be studied and implemented across other regions.

---

# Dashboard Overview

## Page 1 — Executive Summary

Features:

* KPI Cards
* Sales by Category
* Sales by Segment
* Profit by Category
* Profit by Region
* Interactive Filters

Key Purpose:
Provide a high-level overview of business performance.

---

## Page 2 — Profitability Analysis

Features:

* Profit by Sub-Category
* Profit Margin by Category
* Profit by State Map
* Profit by Ship Mode
* Sales vs Profit Analysis

Key Purpose:
Identify profit drivers across products, locations, and shipping methods.

---

## Page 3 — Discount & Loss Analysis

Features:

* Profit by Discount Category
* Profit Margin by Discount Category
* Loss Flag Distribution
* Top Discounted Sub-Categories
* Loss-Making Sub-Categories
* Discount vs Profit Analysis

Key Purpose:
Understand how discounting affects profitability and identify loss-generating products.

---
Dashboard Screenshots
Executive Summary

Add screenshot:
Dashboard Screenshots
Executive Summary

Add screenshot:

dashboard/Screenshorts/page1_executive_summary.png

Profitability Analysis

Add screenshot:

dashboard/page2_profitability_analysis.png

Discount & Loss Analysis

Add screenshot:

dashboard/page3_discount_loss_analysis.png
dashboard/page1_executive_summary.png

Profitability Analysis

Add screenshot:

dashboard/page2_profitability_analysis.png

Discount & Loss Analysis

Add screenshot:

dashboard/page3_discount_loss_analysis.png
# Project Structure

Retail-Sales-Profitability-Analysis/

├── data/

├── notebooks/

├── dashboard/

│   ├── Retail_Sales_Dashboard.pbix

│   ├── page1_executive_summary.png

│   ├── page2_profitability_analysis.png

│   └── page3_discount_loss_analysis.png

├── README.md

└── requirements.txt

---

# Conclusion

This project demonstrates an end-to-end data analytics workflow, from data preparation and exploratory analysis to business intelligence reporting. The findings highlight the importance of discount management, product profitability monitoring, and data-driven decision-making in retail operations.

## 👤 Author
**Suraj Singh** — M.Sc. Data Science & Analytics, Sharda University
[LinkedIn](https://linkedin.com/in/suraj-singh-ds) |
[GitHub](https://github.com/surajthesun1024-ui)
