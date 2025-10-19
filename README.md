# 🚴‍♂️ BikeStores Sales Insights and Performance Analysis Using SQL

## 📖 Overview
This project analyzes the **BikeStores** database to uncover valuable business insights that can help store owners improve sales performance and optimize inventory decisions.  
The analysis was conducted entirely using **SQL queries**, focusing on sales trends, best-performing brands, top products, and customer behavior.

---

## 🧩 Dataset Description
The **BikeStores** database is a sample dataset from [SQLServerTutorial.net](https://www.sqlservertutorial.net/).  
It consists of two main schemas: **Sales** and **Production**, containing tables such as:
- **Sales Schema**
  - `customers` – Customer information (name, email, phone, etc.)
  - `staffs` – Employee data (salesperson, manager, etc.)
  - `stores` – Store details (city, address, etc.)
  - `orders` – Order transactions
  - `order_items` – Products and quantities per order
- **Production Schema**
  - `products` – Product info (model year, category, brand)
  - `categories` – Product categories
  - `brands` – Bike brands
  - `stocks` – Stock levels per store

---

## 🎯 Business Questions Answered
1. What are the **best-selling brands** and their total revenues?  
2. Which **product categories** perform best for each brand?  
3. What is the **percentage of quantities sold** per category by brand?  
4. Who are the **top customers** by purchase volume?  
5. Which **stores** have the highest total sales?  
6. Who are the **top-performing sales staff** and managers?  
7. How do **sales trends** for top bike categories change over the years (2016–2018)?

---

## 📊 Insights Summary
- **Trek** and **Electra** are the top-performing brands in both quantity and revenue.  
- **Cruisers** and **Mountain bikes** dominate sales across multiple years.  
- Certain brands (like *Ritchey* and *Strider*) underperform and should be stocked in smaller quantities.  
- Customer loyalty is strong among top buyers — ideal for **targeted discounts**.  
- **Baldwin Bikes** store leads in sales performance.  
- **Venita Daniel** and **Marcelene Boyer** are top-performing sales staff under manager **Jannette David**.

---

## 🛠️ Tools and Technologies
- **SQL Server**
- **SQL** (JOINs, GROUP BY, CTEs, Aggregations)
- **Power BI** (for visualization)
- **Data Analysis & Business Intelligence**

---

## 📈 Key Results
- Identified top-performing brands and categories.
- Provided actionable recommendations for inventory management.
- Highlighted store and staff performance to improve business strategy.

---

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/BikeStores-SQL-Analysis.git

