A comprehensive data analysis project using Python to evaluate e-commerce transactional data, uncover underlying purchasing patterns, calculate key business metrics, and provide actionable operational recommendations done in Post Graduation(MSc. Data Science).

---

## 📌 Project Overview

In the rapidly evolving e-commerce sector, understanding customer purchasing behavior, revenue streams, and product performance is critical for sustainable growth. This project analyzes transaction-level sales data to extract meaningful business metrics, identify revenue drivers, evaluate customer segmentation, and provide strategic recommendations to optimize inventory and marketing efforts.

### Key Objectives
- **Data Hygiene & Transformation:** Perform data cleaning, handle missing values, correct data types, and prepare raw logs for analysis.
- **Exploratory Data Analysis (EDA):** Analyze distributions, monthly revenue trends, order volume, and average order value (AOV).
- **Customer Insights:** Identify top customers, analyze purchasing frequency, and evaluate repeat customer behavior.
- **Product & Category Performance:** Pinpoint best-selling items, high-value product categories, and underperforming SKUs.
- **Actionable Insights:** Translate quantitative findings into practical business strategy recommendations.

---

## 🛠️ Tech Stack & Tools

- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Environment / Tools:** Jupyter Notebook / VS Code, Git & GitHub

---

## 📂 Repository Structure

```text
├── data/
│   └── e-commerce_sales_analysis.ipynb # Main exploratory and detailed analysis notebook
├── visualisations/
│   ├── e_commerce_Sales_Report.pdf   # contain the analysis report of data
│   ├── e_commerce_Sales_Report.ppt   # presentation for better understanding
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies
---
```
-
**## 📊 Methodology & Key Steps**
-1. **Data Cleaning & Preprocessing**
- **Handling Missing Values:** Treated null customer IDs and missing product category tags.
- **Type Casting**: Converted timestamp strings to native datetime objects for accurate time-series operations.
- **Outlier & Duplicate Removal**: Cleaned duplicate transaction IDs and adjusted extreme edge cases in order quantities and prices.
- **Feature Engineering**: Extracted Year, Month, DayOfWeek, Hour, and computed Total Revenue = Quantity * Unit Price.
--
-2. **Exploratory Data Analysis (EDA)**
- Evaluated overall revenue trajectory across monthly and quarterly intervals.
- Computed performance indicators:
- Total Revenue
- Total Orders
- Unique Customers
- Average Order Value (AOV)
- Analyzed distribution of sales across different time windows to identify peak purchasing hours and days.
--
-3. **Business Analysis & Insights**
- **Product Analysis**: Ranked top 10 products by total revenue vs. total volume sold.
- **Customer Segmentation**: Analyzed revenue contribution from high-value repeat buyers vs. one-time purchasers.
- **Category Trends**: Identified core categories driving bulk profit margins versus entry-level loss leaders.
## 📈 **Summary of Key Results & Insights**
**Revenue Growth**: Sales exhibit significant seasonal spikes during holiday and promotional periods, with Q4 generating the highest monthly revenue share.
**Customer Retention**: A core 20% of repeat customers contribute to over 50% of the total revenue, highlighting the importance of tailored loyalty initiatives.
**Product Concentration**: Top-performing categories maintain steady demand, while low-volume inventory highlights opportunities for stocking optimization. 

                    **-------------------------------------------------------------------------------------------------**
