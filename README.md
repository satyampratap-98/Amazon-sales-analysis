# Amazon Sales Data Analysis – Capstone Project

## 🎯 Project Objective

The primary goal of this project is to analyze sales data from Amazon’s three branches (Mandalay, Yangon, and Naypyitaw) to uncover insights into customer behavior, product performance, and revenue trends. This analysis helps identify key factors driving sales and supports data-driven decision-making for optimizing business performance.

---

## 🗃️ Dataset Overview

The dataset contains **1,000 sales transactions** with **17 features**, including:

- **Branch, City, Customer Type, Gender**
- **Product Line, Unit Price, Quantity, VAT, Total**
- **Date, Time, Payment Method**
- **COGS, Gross Margin %, Gross Income, Rating**

Each record represents an individual customer purchase.

---

## 🧠 Project Approach

### 1. Data Wrangling
- Built and structured a relational database in MySQL.
- Ensured data integrity by setting `NOT NULL` constraints (no missing values).

### 2. Feature Engineering
- `timeofday`: Categorized purchase time into Morning, Afternoon, Evening.
- `dayname`: Extracted the day of the week.
- `monthname`: Extracted the month of the transaction.

### 3. Exploratory Data Analysis (EDA)
Performed in-depth SQL-based analysis to answer key business questions:

- **Product Analysis:** Identified high-performing product lines and underperformers.
- **Sales Analysis:** Assessed monthly revenue, sales peaks, and temporal trends.
- **Customer Analysis:** Analyzed customer types, gender trends, revenue contributions, and VAT distribution.

---

## 🔍 Key Business Questions Answered

- Which product line generated the highest revenue?
- What is the peak sales time of day and day of the week?
- Which customer type contributes the most to revenue?
- Which city recorded the highest revenue and VAT?
- What are the top-rated branches and product lines?
- How do gender and customer type influence purchasing patterns?

---

## 🛠️ Tools & Technologies Used

- **SQL (MySQL):** Data querying, feature engineering, and EDA  
- **DBMS:** MySQL Workbench  
- **Excel:** Initial dataset preparation and inspection  
- **Git/GitHub:** Version control and project sharing  

---

## 📈 Sample SQL Techniques Applied

- Aggregations (`SUM`, `COUNT`, `AVG`)
- Conditional logic (`CASE WHEN`)
- Date/time extraction (`DAYNAME`, `MONTHNAME`, `HOUR`)
- Window functions (`ROW_NUMBER`, `RANK`)
- Subqueries and Common Table Expressions (CTEs)

---

## 📁 Repository Structure

