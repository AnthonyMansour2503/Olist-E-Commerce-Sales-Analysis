# Olist E-Commerce Sales Analysis

## Overview
This project is an end-to-end business intelligence and analytics solution built using Snowflake, SQL, and Power BI. 
The project analyzes the Brazilian Olist e-commerce dataset to uncover insights related to sales performance, product categories, and geographic trends.

## Tools & Technologies
- Snowflake
- SQL
- Power BI
- DAX

## Data Modeling
A star schema was designed to support analytical queries and dashboard visualizations.

### Fact Table
- FACT_ORDERS

### Dimension Tables
- DIM_CUSTOMER
- DIM_SELLER
- DIM_PRODUCTS
- DIM_DATE

## Business Questions Answered
- How does revenue change over time?
- Which product categories generate the most revenue?
- Which states and cities generate the highest sales?
- Who are the top-performing sellers?
- What is the average order value?

## Key Insights
- Revenue trends and seasonality were identified using monthly sales analysis. The revenue peaked in November 2017 with $1 million.
- The highest product categories in terms of revenue are Beleza Saude (Beauty Health), Religios Presentes (Religious Presents), and Cama Mesa Banho (Bed Bath Table) with over $1 million each.
- Sales are heavily concentrated in a small number of Brazilian states and cities, the two largest being Sao Paulo and Rio De Janeiro with nearly $2 million and $1 million respectively.
