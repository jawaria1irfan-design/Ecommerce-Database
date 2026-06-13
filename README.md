# 🗄️ Ecommerce SQL Server Database

A relational Ecommerce database collaboratively designed and built in 
SQL Server, serving as the data foundation for our Python EDA project.

## 👥 Built By
- Jawaria Irfan
- Bint e Rubab

## 📐 Schema Overview

| Table | Primary Key | Foreign Keys |
|---|---|---|
| Category | CategoryID | — |
| Customers | CustomerID | — |
| Products | ProductID | CategoryID |
| Orders | OrderID | CustomerID |
| OrderItems | — | OrderID, ProductID |
| Discounts | DiscountID | ProductID |
| Suppliers | SupplyID | ProductID |
| Reviews | ReviewID | CustomerID, ProductID |

## 📦 What's Included

- Table creation with constraints (Primary Keys, Foreign Keys, Unique, Check)
- Full INSERT statements with realistic sample data
- 15 product categories, 50 products, 100 customers, 100 orders, 50 reviews

## 🔗 Related Project
This database is used as the backend for our EDA project:
👉 [Ecommerce Complete Analysis (Python)](https://github.com/jawaria1irfan-design/Ecommerce-Database/blob/main/Ecommerce%20portfolio%20analysis%20(1).ipynb)

## ▶️ How to Use

1. Open SQL Server Management Studio (SSMS)
2. Run the full script — it creates the `Ecommerce` database automatically
3. All tables and data will be ready to query or connect via Python
