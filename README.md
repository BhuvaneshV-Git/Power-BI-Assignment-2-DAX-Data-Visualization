# Power-BI-Assignment-2-DAX-Data-Visualization
This project focuses on E-Commerce Sales Analysis using Power BI. The objective was to analyze sales data, create key business metrics using DAX (Data Analysis Expressions), and build an interactive dashboard to monitor sales performance, profitability, target achievement, and business trends for data-driven decision-making.
git add README.md
# 📊 DAX & Data Visualization - Power BI

## 📌 Objective

This project focuses on **E-Commerce Sales Analysis** using **Power BI**. The objective was to analyze sales data, create key business metrics using **DAX (Data Analysis Expressions)**, and build an interactive dashboard to monitor sales performance, profitability, target achievement, and business trends for data-driven decision-making.

---

## 🛠️ Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization

---

## 🔄 Project Workflow

1. Import Data
2. Data Cleaning & Transformation
3. Data Modeling & Relationships
4. DAX Calculated Columns & Measures
5. Dashboard Development & Visualization

---

## 📂 Data Preparation

### 📥 Import Data
- Imported all datasets using **Get Data → Text/CSV**

### 🧹 Data Cleaning & Transformation

#### 📋 List of Orders
- Promoted first row as headers
- Removed blank rows
- Validated data using Count and Distinct Count statistics
- Extracted Month Name from Order Date

#### 📦 Order Details
- Converted Amount and Profit to Fixed Decimal Number
- Converted Quantity to Whole Number
- Cleaned and trimmed Category values

#### 🎯 Sales Target
- Extracted Month Name from date fields
- Converted Target column to Fixed Decimal Number
- Loaded transformed data using **Close & Apply**

---

## 🔗 Data Modeling

Created relationships between:

- **Order Details** (Fact Table)
- **List of Orders** using **Order ID** as the primary key

This relationship enabled accurate aggregation and business analysis across the datasets.

---

## 🧮 DAX Calculations

### 📊 Calculated Columns

- Category Type
- Revenue
- Sales Category
- Profit Status
- Order Size

### 📈 Measures

- Total Orders
- Total Sales
- Total Profit
- YTD Sales

---

## 📊 Dashboard Visualizations

### 📈 Sales Target Achievement by Category
**Visual:** Clustered Column Chart

- Compares Total Sales against Total Target across categories.
- Helps identify target achievement performance.

### 🥧 Max Profit Margin by Category
**Visual:** Donut Chart

- Displays profit margin contribution by category.
- Highlights the most profitable categories.

### 📊 Max Profit Margin & Revenue by Sub-Category
**Visual:** Line and Stacked Column Chart

- Compares revenue and profit margin by sub-category.
- Helps identify high-performing product segments.

### 📉 Monthly Sales Target Trend
**Visual:** Line Chart

- Shows monthly target performance.
- Supports trend analysis and forecasting.

### 🔵 Profit vs Quantity Analysis
**Visual:** Scatter Chart

- Compares profitability against quantity sold.
- Helps identify profitable and underperforming products.

### 🎯 KPI Cards

The dashboard includes the following KPIs:

- Total Sales
- Total Profit
- Total Orders
- Total Target
- Sales Achievement %
- Profit Margin %
- Average Profit in Delhi
- YTD Sales

---

## 📌 Key Insights

✅ Built a complete end-to-end Power BI solution from data preparation to reporting.

✅ Applied DAX functions for business calculations and KPI development.

✅ Designed an interactive dashboard for monitoring sales performance and profitability.

✅ Implemented data modeling, calculated columns, measures, and calculated tables.

✅ Created multiple visualizations to support business intelligence and decision-making.

---

## 📸 Dashboard Preview

> Add dashboard screenshots here

```text
Project Structure
│
├── Dataset
│   ├── List of Orders.csv
│   ├── Order Details.csv
│   └── Sales Target.csv
│
├── Power BI File
│   └── DAX_AND_DATA_VISUALIZATION.pbix
│
├── Dashboard Images
│   └── Dashboard.png
│
└── README.md
```

---

## 🎯 Conclusion

This project demonstrates the effective use of **Power BI** for E-Commerce Sales Analysis. Through data modeling, DAX calculations, and interactive visualizations, the dashboard provides valuable insights into sales performance, profitability, and target achievement.

The analysis supports informed business decisions and highlights opportunities for business growth and optimization.

---

## 👨‍💻 Author

### Bhuvanesh V

**Technology:** Power BI | DAX | Data Visualization | Business Intelligence

**Project Type:** E-Commerce Sales Analysis Dashboard

---

⭐ If you found this project helpful, feel free to star this repository.
