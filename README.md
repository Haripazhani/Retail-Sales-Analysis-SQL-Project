# Retail Sales Analysis SQL Project

## Project Overview
Project Title: Retail Sales Analysis  
Level: Beginner  
Database: p1_retail_db  
Last Updated: [Date]

## Project Description
This project is designed to demonstrate SQL skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions through SQL queries.

## Technical Stack
- SQL Database: [MySQL/PostgreSQL/etc.]
- Version Control: GitHub
- Additional Tools: [Any other tools used]

## Database Schema
```sql
CREATE DATABASE p1_retail_db;

CREATE TABLE retail_sales (
    transactions_id INT PRIMARY KEY,
    sale_date DATE,    
    sale_time TIME,
    customer_id INT,    
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,    
    cogs FLOAT,
    total_sale FLOAT
);
