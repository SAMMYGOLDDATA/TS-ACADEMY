# 📊 Gadget Sales Dashboard | Power BI

## 📖 Project Overview

The **Gadget Sales Dashboard** is an interactive Power BI project designed to provide actionable insights into gadget sales performance. The dashboard enables stakeholders to monitor key business metrics, evaluate product and customer performance, and support data-driven decision-making through dynamic visualizations and filters.

This project demonstrates the use of **Power BI**, **Power Query**, **DAX**, and **data modeling** to transform raw sales data into an intuitive business intelligence solution.

---

## 🎯 Business Objectives

The dashboard was developed to:

- Monitor overall business performance.
- Analyze revenue, profit, and purchase costs.
- Identify the most profitable brands.
- Evaluate customer purchasing behavior.
- Compare profitability across income levels.
- Track customer trends over time.
- Analyze purchasing patterns by product color.
- Provide interactive filtering by category and region.

---

## 📂 Dataset

The project is built using three related tables.

### **Sales**
Contains transactional sales data.

| Column |
|---------|
| SaleID |
| ProductID |
| CustomerID |
| Quantity |
| Sales Date |
| Sales Amount |
| Unit Cost |
| Revenue |
| Purchase |
| Profit |

---

### **Products**

Contains product information.

| Column |
|---------|
| ProductID |
| Product Name |
| Category |
| Brand |
| Color |
| Weight |

---

### **Customers**

Contains customer demographic information.

| Column |
|---------|
| CustomerID |
| Customer Name |
| Region |
| Age |
| Gender |
| Income Level |
| Registration Date |

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Modeling

---

## ⭐ Dashboard KPIs

| KPI | Value |
|------|-------|
| Total Revenue | **3.106M** |
| Total Profit | **932K** |
| Total Purchase Cost | **2.174M** |
| Total Customers | **250** |

---

## 📈 Dashboard Features

- KPI Cards
- Brand Profit Analysis
- Revenue Analysis
- Profit by Customer Income Level
- Purchase Distribution by Product Color
- Monthly Customer Trend
- Interactive Region Filter
- Interactive Category Filter

---

## 🏗 Data Model

The project follows a **Star Schema**.

### Fact Table

- Sales

### Dimension Tables

- Customers
- Products

### Relationships

- Customers → Sales *(One-to-Many)*
- Products → Sales *(One-to-Many)*

This model improves report performance and enables efficient filtering across visuals.

---

## 📊 Key Business Insights

- Generated **3.106 Million** in total revenue.
- Achieved a total profit of **932K**.
- Apple recorded the highest profit among all brands.
- Medium-income customers generated the highest overall profit.
- White-colored products were purchased more frequently than Gray and Black products.
- Customer activity declined in February before increasing again in March.
- Interactive filters allow quick comparison across regions and product categories.
- Electronics and Accessories remain the primary product categories driving sales.

---

## 💡 Recommendations

- Increase inventory for high-performing brands such as Apple.
- Develop targeted marketing campaigns for medium-income customers.
- Investigate factors responsible for the February sales decline.
- Expand the availability of high-demand product colors.
- Introduce promotional strategies for lower-performing brands.
- Monitor regional sales to identify growth opportunities.



## 📁 Repository Structure

```
📦 Gadget-Sales-Dashboard
│
├── Data
│   └── Power BI Project TSA.xlsx
│
├── Dashboard
│   └── Gadget Sales Dashboard.pbix
│
├── Images
│   └── dashboard.png
│
└── README.md
```

---

## 🎯 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Star Schema Design
- DAX Measures
- Business Intelligence
- Dashboard Design
- Data Visualization
- KPI Development
- Analytical Storytelling

---

## 🚀 Conclusion

This dashboard transforms raw transactional data into meaningful business insights through interactive visualizations and KPI monitoring. It enables business users to evaluate performance, identify trends, and make informed decisions based on sales, customer, and product data.

---

## 👨‍💻 Author

**Samson Ogunniyi**

Aspiring Data Analyst passionate about transforming data into actionable business insights using Excel, SQL, Power BI, and Python.

### Connect with me

- **LinkedIn:** *www.linkedin.com/in/samson-o-ogunniyi-0130073ab*
