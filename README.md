# Bike Store Sales Analysis

This project focuses on analyzing a Bike Store database using MySQL to extract meaningful business insights from sales, customers, and product data.

Project Overview

The goal of this project is to:

Analyze sales performance
Understand customer and order trends
Identify top-performing products
Practice advanced SQL concepts using a real-world dataset

The dataset represents a bike retail business and includes multiple related tables such as:

products
orders
order_items
customers
stocks

An EER diagram is included to understand table relationships.

Key Analysis Performed

🔹 Product Analysis
Top 5 most expensive products
Top-selling products based on quantity
High-performing products with sales thresholds

🔹 Order Analysis

Orders filtered by status and shipping details
Year-wise order trends (e.g., 2017, 2018)

🔹 Customer Analysis

Orders joined with customer data
Customer-wise order tracking

SQL Concepts Used

This project demonstrates strong SQL fundamentals and intermediate/advanced concepts:

✅ SELECT, WHERE, ORDER BY, LIMIT
✅ JOINS (INNER JOIN, LEFT JOIN, RIGHT JOIN)
✅ GROUP BY & HAVING
✅ Aggregate Functions (SUM, AVG)
✅ Window Functions (DENSE_RANK, ROW_NUMBER)
✅ Date Functions (MONTHNAME, filtering by date range)
✅ Stored Procedures
✅ Table Alteration & Updates

Advanced Analysis

🔸 Ranking Products by Sales

Used DENSE_RANK() to rank products based on total quantity sold
Category-wise ranking using partitioning

🔸 Monthly Sales Insights

Created stored procedure:
AvgSalesPerMonth()
Calculates average monthly sales

🔸 Custom Query Procedures

OrdersByGender(city) → Retrieves orders by customer city
OrdersByProductName(prod_name) → Filters orders by product

🛠️ Tools Used

MySQL
MySQL Workbench

Key Learnings

Writing efficient multi-table joins
Using window functions for ranking and insights
Creating reusable stored procedures
Transforming raw data into meaningful business insights
