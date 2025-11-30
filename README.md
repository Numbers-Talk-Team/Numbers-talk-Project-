# Brazilian Olist Store Data Analysis

This project provides a full end-to-end analysis of the **Brazilian Olist Store Dataset**.  
It includes data cleaning using Python, data modeling using SQL, and building an interactive dashboard using Power BI.

---

## 📌 1. Introduction
The goal of this project is to explore and analyze the Olist e-commerce dataset to extract meaningful insights about customers, sellers, orders, products, and revenue.  
The project aims to help understand marketplace behavior and support data-driven decision-making.

---

## 🎯 2. Project Objectives
- Analyze customer base and geographical distribution  
- Measure seller activity and performance  
- Calculate revenue, profit, and sales trends  
- Identify top-selling products and categories  
- Build a complete data analysis workflow (Python → SQL → Power BI)

---

## 🗂️ 3. Dataset Description
The dataset contains multiple tables related to the Olist e-commerce platform, including:

- Customers  
- Sellers  
- Orders  
- Order Items  
- Products  
- Payments  
- Reviews  
- Geolocation  

The data is publicly available on Kaggle.

---

## 🛠 4. Tools & Technologies Used
- **Python** → Data cleaning & preprocessing  
- **SQL (MySQL/PostgreSQL)** → Creating relationships & joining tables  
- **Power BI Desktop** → Visualization & dashboard creation  
- **GitHub** → Project hosting and version control  

---

## 🧹 5. Data Cleaning (Python)
Data preprocessing was performed using Python (Pandas, NumPy).  
Main cleaning tasks included:

- Removing duplicates  
- Handling missing values  
- Fixing inconsistent formats  
- Cleaning and standardizing datetime columns  
- Renaming columns for clarity  
- Exporting cleaned tables to SQL database  

Examples:
- Converting order purchase timestamps to datetime  
- Fixing category name inconsistencies  
- Validating numeric fields like price and freight value  

---

## 🧩 6. Data Modeling (SQL)
SQL was used to create a relational schema and define relationships between tables.

Main SQL tasks:
- Creating tables with primary and foreign keys  
- Building relationships:  
  - Customers ↔ Orders  
  - Orders ↔ Order Items  
  - Sellers ↔ Order Items  
  - Products ↔ Order Items  
- Creating analytical views for Power BI  
- Joining tables to calculate revenue, order counts, and product performance  

---

## 📊 7. Power BI Dashboard Overview
The interactive Power BI dashboard includes the following insights:

### **Customer Insights**
- Total number of customers  
- Distribution by state and region  
- Customer order trends  

### **Seller Insights**
- Total number of sellers  
- Seller performance metrics  
- Contribution to total sales  

### **Revenue & Profit Analysis**
- Total revenue  
- Total profit  
- Monthly and yearly sales trends  
- Average order value  

### **Product Insights**
- Top-selling products  
- Most profitable categories  
- Review score distribution  

---

## 🏁 8. Key Findings
- Sales volume is higher in certain regions compared to others  
- A small percentage of sellers drive a major portion of revenue  
- Some categories consistently generate higher profit  
- Late deliveries tend to reduce customer satisfaction (review score)

---

## 📥 9. How to Use This Project
1. Download the compressed Power BI file (`.zip`)  
2. Extract the file to obtain the `.pbix` dashboard  
3. Open it using **Power BI Desktop**  
4. Interact with the visuals and filters to explore insights  

SQL scripts and Python notebooks are included in the repository for reproducibility.

---

## 🚀 10. Future Improvements
- Add predictive models (sales forecasting)  
- Build customer segmentation using clustering  
- Automate ETL workflow with Python or Airflow  
- Create a real-time analytics dashboard  

---

## ✔ Project Structure
