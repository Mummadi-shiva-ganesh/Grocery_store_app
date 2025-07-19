# 🛒 Grocery Store Web App

A fully functional grocery store web application built with **Python**, **Flask**, and **MySQL**. This project simulates a real-world inventory management system, allowing users to manage products, units of measure, and pricing seamlessly.

![Homepage Screenshot](https://github.com/codebasics/python_projects_grocery_webapp/raw/main/homepage.JPG)

---

## 🚀 Features

- 🧾 Add, update, and delete **Products**
- 📦 Manage **Units of Measurement (UOM)** like kg, liter, piece, etc.
- 💰 Set and update **Price Per Unit**
- 🔍 View product list with associated UOM
- 🧠 Clean database schema and optimized queries

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python** | Backend logic |
| **Flask** | Web framework |
| **MySQL** | Database management |
| **HTML/CSS** | Frontend templating |
| **Jinja2** | Template engine for dynamic rendering |

---

## 🧩 Database Schema

```sql
Table: uom
- uom_id (Primary Key)
- uom_name

Table: products
- product_id (Primary Key)
- name
- uom_id (Foreign Key -> uom)
- price_per_unit
