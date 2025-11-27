# 📊 Restaurant Orders Analysis Using SQL

A data exploration project using menu and order datasets.

## 📝 Project Overview
This project analyzes restaurant ordering behavior using SQL to uncover insights related to menu pricing, order frequency, customer purchase patterns, and overall sales performance.
Using the **menu_items** and **order_details** datasets, various SQL queries were executed for data exploration, cleaning, aggregation, and deep analysis.

## 🎯 Objectives
- Understand menu item pricing and category-level trends.
- Analyze ordering patterns and item frequency across all orders.
- Identify most ordered and least ordered menu items.
- Detect high-value orders and calculate revenue generated.
- Combine datasets to derive customer behavior insights.

## 📂 Dataset Description
### 1. menu_items
- `menu_item_id`
- `item_name`
- `category`
- `price`

### 2. order_details
- `order_details_id`
- `order_id`
- `item_id`
- `order_date`

Relationship: `order_details.item_id` ↔ `menu_items.menu_item_id`

## 🧠 Key Analysis Performed
- Total menu item count
- Category-wise price analysis
- Highest and lowest priced items
- Total orders & ordering date range
- Items per order distribution
- Most ordered & least ordered items
- Top 5 highest spend orders
- Revenue analysis by item and category
- Combined table analysis using JOIN

## 📌 SQL Concepts Used
- SELECT, WHERE, ORDER BY
- GROUP BY, COUNT, SUM, AVG
- MIN, MAX
- JOIN (INNER JOIN)
- Aggregation & filtering
