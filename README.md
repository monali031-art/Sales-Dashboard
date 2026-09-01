# 📊 Sales Performance Dashboard | Power BI

An interactive **Sales Performance Dashboard** built using **Microsoft Power BI** to analyze sales, profit, orders, products, regions, categories, and salesperson performance.

The dashboard provides a clear overview of business performance and helps identify top-performing products, regions, categories, and salespersons.

---

## 🖼️ Dashboard Preview

![Sales Performance Dashboard](<img width="1920" height="1020" alt="Screenshot 2026-09-01 210721" src="https://github.com/user-attachments/assets/b3231de3-7103-4aee-9487-a97727a0b1fa" />
)

---

**📌 Project Overview**

This project presents an interactive Sales Performance Dashboard developed using Microsoft Power BI.

The dashboard transforms raw sales data into meaningful business insights through KPIs, charts, interactive filters, and DAX measures.

It helps users understand overall sales performance, profitability, regional performance, product performance, and salesperson contribution.

---

**🛠️ Tools & Technologies**

- Microsoft Power BI
- DAX
- Microsoft Excel
- Data Modeling
- Data Visualization
- Business Intelligence

---

**📂 Dataset**

The dataset contains 500 sales transactions for the year 2025.

Dataset Includes

- Order ID
- Order Date
- Region
- Category
- Product
- Salesperson
- Customer
- Quantity
- Unit Price
- Discount
- Gross Sales
- Discount Amount
- Sales
- Cost
- Profit

A separate Date Table is also included for time-based analysis.

---

**📊 Dashboard KPIs**

KPI| Description
💰 Total Sales| Overall sales revenue
📈 Total Profit| Total profit generated
🧾 Total Orders| Number of unique orders
📦 Total Quantity| Total units sold
🎯 Profit Margin| Profit as a percentage of sales

---

**📈 Dashboard Features**

1. Monthly Sales Trend

Shows monthly sales performance and helps identify changes and trends throughout the year.

2. Sales by Region

Compares sales performance across different regions:

- North
- South
- East
- West

3. Sales by Category

Displays the contribution of different product categories to total sales.

4. Top 10 Products

Identifies the top 10 products based on sales revenue.

5. Profit by Category

Compares profitability across different product categories.

6. Sales by Salesperson

Analyzes individual salesperson performance based on total sales.

7. Interactive Slicers

The dashboard includes interactive filters for:

- 🌍 Region
- 🗂️ Category
- 📅 Date Range

Selecting a filter dynamically updates the dashboard visuals.

---

**🧮 DAX Measures**

Total Sales

Total Sales = SUM('Sales Data'[Sales])

Total Profit

Total Profit = SUM('Sales Data'[Profit])

Total Orders

Total Orders = DISTINCTCOUNT('Sales Data'[Order ID])

Total Quantity

Total Quantity = SUM('Sales Data'[Quantity])

Profit Margin

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

---

**🔗 Data Model**

The project uses a simple data model with:

Sales Data → Fact Table

Date Table → Dimension Table

Relationship:

"Sales Data[Order Date] → Date Table[Date]"

This relationship enables accurate monthly and date-based analysis.

---

**💡 Key Business Insights**

The dashboard helps identify:

- Best-performing product categories
- Top-selling products
- Highest-performing regions
- Salesperson performance
- Monthly sales trends
- Overall profitability
- Profit margin performance

---

**🎯 Project Objective**

The objective of this project is to demonstrate how raw sales data can be transformed into an interactive Business Intelligence dashboard using Power BI.

The dashboard provides a simple and effective way for users to monitor business performance and support data-driven decision making.

---

**📁 Project Files**

File| Description
"Sales_Dashboard.pbix"| Power BI dashboard file
"Sales_Dashboard_Data.xlsx"| Source sales dataset
"Dashboard_Screenshot.png"| Dashboard screenshot
"README.md"| Project documentation

---

**🚀 Skills Demonstrated**

- Data Cleaning & Preparation
- Data Modeling
- DAX
- KPI Development
- Data Visualization
- Interactive Dashboard Design
- Business Intelligence
- Sales Analysis
- Profitability Analysis

---

**👩‍💻 Project Type**

**Power BI Portfolio Project**

Project: Sales Performance Dashboard
Tool: Microsoft Power BI
Dataset: Excel
Year: 2025
