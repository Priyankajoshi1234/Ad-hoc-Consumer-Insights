# AtliQ Hardware Ad-Hoc Insights  

This repository contains the SQL-based ad-hoc analysis project for **AtliQ Hardware**, a hardware manufacturing company specializing in electronic devices and sales products like PCs, printers, and accessories. The objective of this project is to deliver actionable business insights based on ten key business requests.

---

## 📊 **Project Overview**  

**Company Context:**  
AtliQ Hardware operates in multiple regions, including India, China, Korea, APAC, and Latin America, using various sales channels like Retailers, Direct Stores, and Distributors.  

**Problem Statement:**  
The management team lacked actionable insights to make informed decisions, prompting the need for an ad-hoc analysis to generate key business metrics.

**Objective:**  
Generate insights for 10 business requests using SQL, visualize results, and present findings to stakeholders.

## 🛠️ **Project Components**

### **1. SQL Queries**  
All SQL queries for the 10 ad-hoc business requests can be found in the `sql_queries/` folder. Each query corresponds to a specific business request.

### **2. Visualizations**  
Charts and dashboards visualizing the outputs of SQL queries are stored in the `visualizations/` folder. These visualizations are designed to provide stakeholders with actionable insights.

### **3. Datasets**  
- **Raw Data:** Original data files are located in the `data/raw/` directory.
- **Processed Data:** Cleaned datasets used for analysis are in `data/processed/`.

### **4. Documentation**  
Detailed insights, methods, and results are documented in the project report located in `docs/AtliQ_Hardware_Insights_Report.pdf`.

---

## 📋 **Business Requests and Insights**  

| **Request** | **Description** | **Key Insight** |
|-------------|-----------------|-----------------|
| 1           | Markets in APAC region where "AtliQ Exclusive" operates. | Operates in 8 countries. |
| 2           | % Increase in unique products (2021 vs. 2020). | 36.33% increase in unique products. |
| 3           | Unique product counts by segment (sorted). | Notebook has the highest count; Storage the lowest. |
| 4           | Segment with the highest growth (2021 vs. 2020). | Accessories grew by 34 products. |
| 5           | Product with the highest and lowest manufacturing costs. | Desktop: Highest; Mouse: Lowest. |
| 6           | Top 5 customers with high pre-invoice discounts (India, 2021). | Flipkart received the highest discounts. |
| 7           | Monthly gross sales for "AtliQ Exclusive." | Nov: Highest; Aug: Lowest in 2021. |
| 8           | Quarter with maximum sold quantity in 2020. | Q1 had the highest sold quantity. |
| 9           | Sales channel contribution in FY 2021. | Retailer: 72%; Direct: 16%; Distributor: 11%. |
| 10          | Top 3 products by division (FY 2021). | Details included in visualizations. |

---

