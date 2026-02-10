# Customer Behavior Analysis in E-commerce

This repository contains a data analysis project focused on understanding customer purchasing behavior in an e-commerce environment using real transactional data.
The analysis aims to explore customer recurrence, revenue concentration, purchase distribution, and product performance through exploratory data analysis and data visualization.

---
## Dataset Description

The dataset contains e-commerce transaction records, including:
- Invoice identifiers
- Product codes and descriptions
- Quantities and unit prices
- Transaction dates
- Customer identifiers
- Country information
  
The data has been cleaned to remove missing customer IDs, invalid transactions (negative quantities or prices), and inconsistent entries.

---
## Objectives

The main objectives of this project are to answer the following questions:
- How many customers purchase more than once?
- Are there occasional versus recurring customers?
- Are there high-value customers?
- How is revenue distributed across customers?
- How does customer activity evolve over time?
- Which products generate the highest revenue?
- How concentrated is the total revenue among top customers?
  
---
## Methodology

The analysis follows a structured workflow:
1. Data loading and initial inspection  
2. Data cleaning and preprocessing  
3. Feature engineering (calculation of total transaction revenue)  
4. Exploratory data analysis (EDA)  
5. Visualization of key insights  
6. Interpretation of results  

The analysis is performed using Python and common data analysis libraries.

---
## Key Findings

- Most customers make a limited number of purchases.
- A relatively small fraction of customers generates a significant share of the total revenue.
- Approximately 10% of customers account for about 60% of the total revenue, indicating a strong revenue concentration among high-value customers.
- This behavior is consistent with typical real-world e-commerce dynamics, where customer value is highly heterogeneous.
  
