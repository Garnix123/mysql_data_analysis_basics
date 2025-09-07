# 🌿 Lucky Shrub – MySQL Data Analysis Basics

This repository contains a **SQL practice project** designed around a fictional landscaping and gardening company called **Lucky Shrub**.  
It demonstrates how to create relational database structures, populate them with sample data, and run analytical queries to answer real business questions.  

---

## 📂 Project Overview
The project simulates the workflow of a data analyst tasked with helping Lucky Shrub gain insights into their clients, products, and sales.  
It includes:
- **Database creation** (`USE Lucky_Shrub;`)
- **Table design** (Clients, Orders, Products, Addresses)
- **Sample data insertion** (clients, products, orders, addresses)
- **SQL tasks and solutions** that replicate business problems analysts often face.

---

## 🗂️ Database Schema
Four main tables were created:

- **Clients**: Stores customer details  
- **Orders**: Contains purchase transactions  
- **Products**: Holds inventory and pricing data  
- **Addresses**: Maps client addresses  

These are connected via primary and foreign keys, simulating a real-world relational structure.  

---

## 📝 SQL Tasks

### **Task 1 – Product Sales by Year**
> *How many sycamore trees (ProductID = `P4`) were sold in 2020, 2021, and 2022?*  
✔ Demonstrates filtering with `WHERE`, aggregation with `SUM`, and year-based grouping.

---

### **Task 2 – Client Orders in 2021 & 2022**
> *Retrieve all clients and their orders for the years 2021 and 2022.*  
✔ Uses `INNER JOIN` across multiple tables to enrich data with client and product information.  

---

### **Task 3 – Sales Function**
> *Analyze the sales performance of any product in a given year.*  
✔ Implements a **custom SQL function** `FindSoldQuantity(product_id, year)` that calculates total units sold.  
✔ Reusable for different products and years.  

---

## 🎯 Why This Matters
- 📊 **Business relevance**: Shows how SQL answers real business questions.  
- 🏗 **Database fundamentals**: Covers table design, keys, joins, aggregation, and user-defined functions.  
- 🔍 **Analytical skills**: Emphasizes querying techniques for sales and client analysis.  
- ♻ **Reusability**: Functions like `FindSoldQuantity` reduce repetitive code.  

This project strengthens **core SQL skills** that every data analyst or BI professional uses daily.  

---

## 🚀 How to Use
1. Clone the repository.  
2. Run the SQL script in **MySQL Workbench** (or any MySQL-compatible environment).  
3. Execute the queries step by step to reproduce results.  
4. Modify product IDs or years to experiment with different scenarios.  

---

## 📬 Contact
If you have questions or suggestions, feel free to reach out:  

- **LinkedIn**: [Dominik Vyleta](https://www.linkedin.com/in/dominik-vyleta-mba-a566511b2/)  
- **GitHub**: [Garnix123](https://github.com/Garnix123)  
- **Email**: vyleta.dom@gmail.com  

---
