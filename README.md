# 🍽️ Restaurant Operations Analysis (SQL Project)

This project involves a detailed analysis of restaurant order data using **MySQL** to uncover valuable business insights. It uses two main tables — `menu_items` and `order_details` — to identify customer behavior, dish popularity, sales trends, and potential areas for menu optimization.

---

## 📁 Dataset

The dataset contains two tables:

1. **menu_items**  
   Contains information about each dish on the menu.
   - `menu_item_id`
   - `item_name`
   - `category`
   - `price`

2. **order_details**  
   Contains all item-level order transactions with timestamps.
   - `order_details_id`
   - `order_id`
   - `order_date`
   - `order_time`
   - `item_id`

---

## 🎯 Project Objectives

### ✅ Objective 1: Menu-Level Analysis
- Count total items on the menu.
- Identify the **most** and **least** expensive dishes.
- Filter and count **Italian dishes**.
- Find average price per category.

### ✅ Objective 2: Order-Level Analysis
- Find date range and total number of orders.
- Identify orders with the most items.
- Count how many orders contained more than 12 items.

### ✅ Objective 3: Joined Insights
- Join `order_details` with `menu_items` for full analysis.
- Identify:
  - **Most/least ordered dishes**
  - **Top 5 highest spending orders**
  - Insights into **category-wise spending**
  - Dishes and categories contributing to top orders

---

## 🧠 Key Insights

- **Italian dishes** are highly popular with higher average prices.
- A small number of orders accounted for the majority of revenue.
- **“Item 117”** (for example) was among the most frequently ordered dishes.
- Many orders contained **more than 12 items**, indicating group or family orders.
- Certain categories had many items but low purchase frequency, suggesting scope for menu simplification.

---

## 🛠️ Tools & Skills Used

- **MySQL**
- SQL Joins (`INNER`, `LEFT JOIN`)
- Aggregate Functions (`SUM`, `COUNT`, `AVG`)
- Filtering (`WHERE`, `HAVING`)
- Sorting (`ORDER BY`)
- Subqueries

---

## 📂 How to Run

1. Open MySQL Workbench or any SQL environment.
2. Run the `Restaurant Order SQL-Project.sql` script to create the schema and insert data.
3. Start querying based on the objectives above.

---

## 📌 Project Status

✅ Completed  
🔍 Open to feedback and improvement suggestions

---


