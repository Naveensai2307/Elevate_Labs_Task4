# 📊 Sales Financial Dashboard | Power BI
---

# 📌 Project Overview

The **Sales Financial Dashboard** is an interactive Business Intelligence dashboard developed using **Microsoft Power BI Desktop** to analyze the financial performance of a global sales dataset. The dashboard provides decision-makers with a comprehensive overview of key business metrics including **Sales, Profit, Gross Sales, Units Sold, and Profit Margin**.

The dashboard enables users to monitor business performance across multiple dimensions such as **Country, Product, Customer Segment, Month, Year, and Discount Band** through interactive slicers and dynamic visualizations. It combines KPI cards, line charts, bar charts, donut charts, scatter plots, waterfall charts, combo charts, and treemaps to uncover sales trends, profitability, product performance, customer segmentation, and the impact of discounts on business revenue.

---

# 📂 Dataset Description

The project uses the **Financial Sample Dataset**, which contains transactional sales information collected from multiple countries over different time periods.

### Dataset Features

| Feature | Description |
|----------|-------------|
| Segment | Customer Segment |
| Country | Sales Country |
| Product | Product Name |
| Discount Band | Discount Category |
| Units Sold | Quantity Sold |
| Manufacturing Price | Manufacturing Cost |
| Sale Price | Selling Price |
| Gross Sales | Total Revenue Before Discount |
| Discounts | Discount Amount |
| Sales | Net Sales |
| COGS | Cost of Goods Sold |
| Profit | Net Profit |
| Date | Transaction Date |
| Month Number | Numeric Month |
| Month Name | Month Name |
| Year | Transaction Year |

---

# 🚀 Technologies Used

| Technology | Purpose |
|------------|---------|
| Microsoft Power BI Desktop | Dashboard Development |
| DAX (Data Analysis Expressions) | Calculated Measures |
| Power Query | Data Preparation |
| Microsoft Excel | Dataset Source |
| Data Visualization | Business Intelligence |

---

# ⚙ Installation Steps

### 1 Clone the Repository

```bash
git clone https://github.com/Naveensai2307/Elevate_Labs_Task4.git
```

### 2 Open Power BI

Open

```
Sales Financial Dashboard.pbix
```

using

```
Microsoft Power BI Desktop
```

### 3 Refresh Dataset

Home

➡ Refresh

### 4 Explore Dashboard

Use the interactive slicers to filter the report by

- Slicer for Year
- Slicer for Country
- Slicer for Segment
- Slicer for Product
- Slicer for Month Name
- Slicer for Discount Band

---

# 📈 Dashboard Features

## KPI Cards

✔ Total Sales

✔ Total Profit

✔ Gross Sales

✔ Units Sold

✔ Profit Margin (sum of profit / sum of sales)

---

## Interactive Filters

- Year
- Country
- Product
- Segment
- Month Name
- Discount Band

---

## Visualizations

### 📉 Line Charts

- Sales by Month Name
- Sales by Month Number
- Profit by Month Name
- Profit by Month Number

### 📊 Bar Charts (Stacked chart)

- Sales by Product
- Sales by Country
- Profit by Country
- Profit by Segment

### 🍩 Donut Chart

- Sales by Segment

### 🟦 Treemap

- Profit by Product

### 📈 Scatter Plot

- Discounts vs Profit (Discounts, Profit and Sales by Discount Band)

### 📉 Waterfall Chart

- Profit by Country and Segment

### 📊 Combo Chart (Line and Stacked column chart)

- Sales and Profit by Country and Segment

These visualizations enable users to compare monthly performance, evaluate country-wise profitability, analyze product contributions, examine customer segments, and understand how discounts affect profit.

---

# 🔄 Project Workflow

```text
Financial Dataset
        │
        ▼
Data Import (Excel)
        │
        ▼
Power Query
(Data Cleaning & Transformation)
        │
        ▼
Data Modeling
        │
        ▼
DAX Measures
(Profit Margin)
        │
        ▼
Dashboard Design
        │
        ▼
Interactive Filters
        │
        ▼
Business Insights
```

---

# 📊 Dashboard Insights

The dashboard provides several important business insights:

- Total Sales reached **118.73M**.
- Total Profit amounted to **16.89M**.
- Gross Sales totaled **127.93M**.
- More than **1.13M Units** were sold.
- Overall Profit Margin was approximately **14%**.
- Government and Small Business segments generated the highest revenue.
- Paseo emerged as the highest-selling and highest-profit product.
- France recorded the highest profit among all countries.
- The United States generated the highest sales.
- High discount levels did not always translate into higher profits, highlighting the importance of balanced pricing strategies.

---

# 🎯 Results

The developed dashboard successfully delivers:

✅ Executive-level KPI monitoring

✅ Interactive financial reporting

✅ Country-wise sales analysis

✅ Product performance evaluation

✅ Customer segment analysis

✅ Discount impact assessment

✅ Monthly sales and profit trend analysis

✅ Dynamic filtering for better business decision-making

Overall, the dashboard transforms raw financial data into meaningful business insights, enabling faster and more informed decision-making.

---

# 🖼 Dashboard Screenshots

## Dashboard Overview

```
Dashboard_screenshots/
│
├── Financial data.png
```

Add screenshots similar to:

- KPI Cards
- Monthly Sales Trend
- Monthly Profit Trend
- Sales by Segment
- Profit by Country
- Sales by Product
- Scatter Plot
- Waterfall Chart
- Combo Chart

---

# 💡 Future Improvements

- Integrate live SQL Server or Azure SQL Database.
- Enable automatic scheduled data refresh.
- Add drill-through pages for detailed product analysis.
- Include forecasting using Power BI Analytics.
- Develop customer profitability analysis.
- Add regional sales maps.
- Implement Row-Level Security (RLS).
- Publish the dashboard to Power BI Service for online collaboration.

---

# 📁 Repository Structure

```
Sales-Financial-Dashboard/
│
├── Dashboard/
│   ├── Sales Financial Dashboard.pbix
│
├── Dataset/
│   ├── Financial Sample.xlsx
│
├── Screenshots/
│   ├── Dashboard_Page1.png
│   ├── Dashboard_Page2.png
│
├── README.md
├── Task4_Dashboard_Summary.pptx
├── Sales Financial Dashboard.pdf
└── task 4.pdf
```

---

### Skills

- Power BI
- SQL
- Python
- Pandas
- Data Visualization
- Microsoft Excel
- Business Intelligence
- Machine Learning

---


## 👨‍💻 Author

**Name:** Naveen Sai Kumar Aduri

**Internship:** Elevate Labs– Data Analyst Internship

**Task:** Task 4: Dashboard Design (Sales Financial Dashboard)

GitHub: https://github.com/Naveensai2307/Elevate_Labs_Task4.git

LinkedIn: https://www.linkedin.com/in/naveen-sai-kumar-aduri-628001186/
