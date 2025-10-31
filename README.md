# Sales-Profit-Performance-Over-Time
Project Overview

This project analyzes sales performance trends using SQL to calculate month-over-month and year-over-year growth for sales and profit. The analysis helps understand business performance dynamics and category-level profitability trends over time.
An interactive dashboard visualizes the results for easier business insights.

🧮 SQL Logic Summary
'' The analysis is performed in two main steps using CTEs:
# 1)sales_profit_performance CTE
Aggregates sales, profit, and order count by year, month, and category.

## 2)growth CTE
Uses LAG() window functions to calculate:
Previous month’s and previous year’s sales & profit.
Computes MoM and YoY growth metrics. 
