# Retail Sales Analysis SQL Project

## Project Overview
Project Title: Retail Sales Analysis  
Level: Beginner  
Database: p1_retail_db  
Last Updated: [Date]

## Project Description
This project is designed to demonstrate SQL skills and techniques typically used by data analysts to explore, clean, and analyze retail sales data. The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions through SQL queries.

## Objectives
**Set up a retail sales database**: Create and populate a retail sales database with the provided sales data.  
**Data Cleaning**: Identify and remove any records with missing or null values.  
**Exploratory Data Analysis (EDA)**: Perform basic exploratory data analysis to understand the dataset.  
**Business Analysis**: Use SQL to answer specific business questions and derive insights from the sales data.  


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

 
##**Project Structure**

### 1. **Database Setup**

#### **Database Creation:** The project starts by creating a database named p1_retail_db.


```sql
-- Create the retail database
CREATE DATABASE p1_retail_db;
