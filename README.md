# MySQL-Analytics-Report-AtliQ-Hardware
## 📌 Project Overview

SQL Finance Analytics project using the AtliQ Hardware dataset. Includes sales, pricing, customer, product, and market analysis using SQL.
---

## 🎯 Project Objectives

* Analyze customer, product, sales, and pricing data.
* Generate Gross Sales and Net Sales reports.
* Build reusable SQL components using Functions, Views, and Stored Procedures.
* Perform customer and market performance analysis.
* Use CTEs and Window Functions for advanced analytics.
* Create business reports that support data-driven decision making.

---

## 🗄️ Database Tables Used

### Dimension Tables

* dim_customer
* dim_product

### Fact Tables

* fact_sales_monthly
* fact_gross_price
* fact_pre_invoice_deductions
* fact_post_invoice_deductions

### Database Size

* Approximately **1.43 Million Records (1,425,706 rows)**

---

## 🛠️ Key Tasks Performed

### User Defined Functions (UDF)

* Created Fiscal Year Function (`get_fiscal_year`)
* Created Fiscal Quarter Function (`get_fiscal_quarter`)
* Retrieved sales data based on fiscal periods

### Data Analysis Using Joins

* Product-level Sales Analysis
* Gross Sales Calculation
* Monthly Gross Sales Reports
* Yearly Gross Sales Reports

### Stored Procedures

* Monthly Gross Sales Report for any customer
* Market Badge Classification (Gold / Silver)
* Top N Markets by Net Sales
* Top N Customers by Net Sales
* Top N Products by Net Sales

### Database Views

* sales_preinv_discount
* sales_postinv_discount
* net_sales

### Advanced SQL Analytics

* Customer-wise Net Sales Contribution
* Regional Net Sales Distribution
* Top Products by Division
* Top Markets by Region

### CTEs & Window Functions

* DENSE_RANK()
* PARTITION BY
* OVER()
* Percentage Contribution Analysis
* Ranking Analysis

---

## 💡 Business Insights Generated

* Identified top-performing markets by net sales.
* Identified top customers contributing to company revenue.
* Identified top-selling products across divisions.
* Measured customer contribution percentage globally and region-wise.
* Analyzed the impact of discounts on final net sales.
* Automated reporting using stored procedures and views.

---

## 🚀 Technical Skills Demonstrated

### SQL

* SELECT Statements
* Filtering and Sorting
* Aggregate Functions
* GROUP BY
* HAVING
* ORDER BY

### SQL Joins

* INNER JOIN
* Multi-table Joins

### Advanced SQL

* User Defined Functions (UDF)
* Stored Procedures
* Views
* Common Table Expressions (CTE)
* Window Functions
* DENSE_RANK()
* PARTITION BY
* OVER()

### Database Optimization

* Replacing repeated calculations with reusable functions
* Creating reusable views for reporting
* Building dynamic stored procedures

---

## 🤝 Soft Skills Demonstrated

* Understanding business requirements
* Converting business problems into SQL solutions
* Analytical thinking
* Data interpretation
* Report generation
* Presenting insights in a clear and meaningful way

---

## 📂 Project Deliverables

* SQL Queries
* Stored Procedures
* User Defined Functions
* Database Views
* Analytics Reports
* Business Insights Documentation

---

## 📚 Key Learning Outcomes

Through this project, I learned how to:

* Work with large datasets containing over 1 million records.
* Build reusable SQL solutions using functions and procedures.
* Perform sales and finance analytics using SQL.
* Create business reports from raw transactional data.
* Use CTEs and Window Functions for advanced analysis.
* Translate business requirements into actionable SQL queries.

---

## 🔗 Project Report

The complete project report with SQL queries, outputs, and explanations is available in this repository.

**Report File:** `AtliQ Hardware SQL Report.pdf`

---
