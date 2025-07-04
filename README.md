# Kultra_Stores-Inventory
##✅ Initial Understanding
Client: Kultra Mega Stores (KMS)
Location: Abuja Division
Time Period: 2009–2012
Data Format: Excel file (contains order data)
Goal: Perform a comprehensive data analysis and deliver insights to help the Business Manager with decision-making.

## 🧮 Step 1: Understand the Dataset Structure
I’ll inspect the columns, data types, and a sample of the data so we can design appropriate SQL queries for both scenarios.

## To proceed with the analysis, I’ll need the two case scenarios you referred to earlier (from my DSA class document). 
They usually include specific business questions like:
Top-selling products or categories
Profitability by region or customer segment
Recommendations to improve revenue

## 1. Which product category had the highest sales?
Group data by Product Category
Sum Sales for each
Rank descending to find the top one

## 🔍 2. What are the Top 3 and Bottom 3 regions in terms of sales?
Group by Region
Sum Sales
Sort descending for Top 3
Sort ascending for Bottom 3

##🔍 3. What were the total sales of appliances in Ontario?
Filter where Category = 'Appliances' AND Region = 'Ontario'
Sum the Sales

## 🧠 4. Advise KMS on how to increase revenue from the bottom 10 customers
Rank customers by total sales
Select bottom 10
Provide insight based on:
Purchase frequency
Product mix
Discount levels
Location and shipping methods

and the rest of others
