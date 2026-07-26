Pizza-Sales-Analysis-SQL-Database
SQL project where I built a relational database and analyzed real-world e-commerce sales records. The goal here was to act like a lead data analyst: structuring raw transaction data into clean tables and pulling actionable business insights about revenue, rush hours, menu performance, and order patterns.


🍕 E-Commerce Pizza Sales Analysis (Database & SQL Analytics)

[![SQL Database](https://img.shields.io/badge/Database-PostgreSQL%2FMySQL-blue?style=flat&logo=postgresql)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

 📌 Project Overview
 
This project involves building a relational database schema from scratch and running end-to-end exploratory SQL data analysis on an e-commerce pizza store dataset containing **~48,000 sales transactions**. 

The goal is to translate raw order logs into actionable business insights regarding **revenue drivers, peak order periods, menu performance, and inventory trends**.



🎯 Key Business Questions Addressed
1. KPI Metrics: What is the total revenue, total orders placed, average order value, and average pizzas per order?
2. Sales Trends: What hours and days witness peak ordering traffic?
3. Menu Performance: Which pizza categories and sizes generate the highest vs. lowest sales?
4. Customer Behavior: What are the top 3 best-selling pizzas per category?


🛠️ Data Architecture & Schema
The relational database consists of 4 main tables structured to eliminate redundancies:
- `orders`: Transaction timestamps.
- `order_details`: Line items per order.
- `pizzas`: Size and pricing tiers.
- `pizza_types`: Category and ingredient metadata.

![ERD Diagram](outputs/ERD_diagram.png)



💡 Key Insights & Findings

- Peak Ordering Hours:** Highest order volume occurs between **12:00 PM - 1:00 PM** (lunch rush) and **6:00 PM - 8:00 PM** (dinner rush).
- Top Revenue Generator:** **The Thai Chicken Pizza** generated the highest total revenue ($43,434), despite **The Classic Deluxe** having higher unit sales.
- Size Distribution:** **Large (L)** size pizzas account for **~45%** of total revenue, whereas Small (S) accounts for only 15%.


