
# 🛍️ E-Commerce Database System

## 📌 Project Overview
A **MySQL database** for an online store, designed for a university assignment. Features:
- Customer accounts & profiles
- Product inventory management
- Order processing system
- Payment tracking

## 🛠️ Technical Specifications
- **Database**: MySQL 8.0+
- **Tables**: 5 (customers, products, orders, order_items, payments)
- **Relationships**: 1-to-many (e.g., customers → orders) and many-to-many (via junction tables)

## 🚀 Setup Guide

### Prerequisites
- MySQL Server ([Download](https://dev.mysql.com/downloads/))
- MySQL Workbench (Recommended)

### Installation
1. **Import the database**:
   ```bash
   mysql -u root -p < ecommerce_database.sql

    Key Features
Data Integrity: Primary/Foreign keys, constraints
Scalability: Normalized structure for growth
Documentation: Well-commented SQL

