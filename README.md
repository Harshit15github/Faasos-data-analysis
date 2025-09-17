# 🍴 FAASOS Dummy Dataset Analysis – SQL Project

## 📌 Project Overview
This project analyzes a **FAASOS dummy dataset** using **SQL** to uncover insights about customer orders, delivery performance, and operational efficiency.  
The focus is on:
- **Data Cleaning & Preprocessing**: Handling missing values, duplicates, and inconsistencies to ensure reliable analysis.  
- **SQL Query Optimization**: Writing efficient queries to extract meaningful insights.  
- **Actionable Insights & Reporting**: Delivering business-ready conclusions for **marketing strategies** and **inventory management**.

---

## 🗂 Dataset Description
The project simulates a food delivery business using multiple relational tables:

- **driver** → Driver registration details  
- **ingredients** → Ingredients available for rolls  
- **rolls** → Veg & Non-Veg roll categories  
- **rolls_recipes** → Recipe mapping of rolls with ingredients  
- **driver_order** → Delivery details (distance, time, cancellations)  
- **customer_orders** → Customer order details (items excluded, extras added, timestamps)

---

## ⚙️ Data Cleaning & Preprocessing
- Handled **null values**, **duplicates**, and inconsistent fields (e.g., “NaN”, blank strings).  
- Standardized **distance**, **duration**, and **cancellation** fields.  
- Created **temporary tables** for cleaned datasets to enable accurate querying.  

---

## 🔍 Key Business Questions Solved
1. **Roll Analysis**
   - How many of each type of roll (Veg vs. Non-Veg) were delivered?  
   - What is the total number of rolls ordered per **customer**?  

2. **Customer Insights**
   - How many rolls did each customer order with **customizations** (exclusions/extras)?  
   - Which customers frequently order **Veg vs. Non-Veg rolls**?  

3. **Operational Metrics**
   - Maximum number of rolls delivered in a single order.  
   - Average time taken for delivery from FAASOS HQ to customer.  
   - Relationship between number of rolls in an order and preparation time.  
   - Average **distance traveled per customer**.  
   - Difference between the **longest and shortest delivery times**.  

4. **Driver Performance**
   - Average delivery **speed per driver**.  
   - Successful delivery percentage for each driver.  

5. **Order Patterns**
   - Number of rolls ordered by **hour of the day**.  
   - Orders grouped by **day of the week**.  

---

## 🛠 SQL Concepts Used
- **Joins** (INNER, LEFT, CTEs for clean structure)  
- **Aggregate functions** (`COUNT`, `AVG`, `SUM`, `MAX`, `MIN`)  
- **Window functions** (`ROW_NUMBER`, `RANK`)  
- **Case statements** for custom logic  
- **CTEs (Common Table Expressions)** for complex queries  

---

## 📈 Sample Insights
- **Veg vs. Non-Veg Preference**: Identified demand split between roll categories.  
- **Customer Ordering Trends**: Found peak order times by hour and weekday.  
- **Delivery Performance**: Detected variations in driver speed and success rates.  
- **Operational Efficiency**: Analyzed impact of customizations on preparation and delivery time.  

---


