#  DSA- Amazon Product Review Analysis (RetailTech Insights) Case study
## Amazon Case Study
## Project Overview
This project contains analysis of an amazon business … based on customers rating 
## Business Introduction 
RetailTech Insights is a company that provides E-commerce analytics solutions to sellers on platforms like Amazon. 

## Aim  
The aim of this project is to analyze product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement. This was done by answering the following business questions:
1. What is the average discount percentage by product category?
2. How many products are listed under each category?
3. What is the total number of reviews per category?
4. Which products have the highest average ratings?
5. What is the average actual price vs the discounted price by category?
6. Which products have the highest number of reviews?
7. How many products have a discount of 50% or more?
8. What is the distribution of product ratings (e.g., how many products are rated 3.0,
4.0, etc.)?
9. What is the total potential revenue (actual_price × rating_count) by category?
10. What is the number of unique products per price range bucket (e.g., <₹200,
₹200–₹500, >₹500)?
11. How does the rating relate to the level of discount?
12. How many products have fewer than 1,000 reviews?
13. Which categories have products with the highest discounts?
14. Identify the top 5 products in terms of rating and number of reviews combined.
## Dataset Description
The dataset contains information scraped from Amazon product pages, including:
-Product details: name, category, price, discount, and ratings
-Customer engagement: user reviews, titles, and content
-Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
Total Records: 1,465 rows
Total Fields: 16 columns.
## Tools
Microsoft Excel 
Excel Pivot tables 
Excel Pivot Charts
Dashboard

## Process 
### Step 1: Data Cleaning and transformation 
-Data was first converted into a table
-Then removed duplicates using ProductID, ReviewID and userID
-Excess space and 
-Standard data format to the appropriate format
-Trimming the category then breaking into subcategories for better summarization.

### Step 2: Data Analysis:
-Created calculated columns for KPI (revenue)
### Step 3: Data Visualization 
-Built Interactive Dashboard using Slicers filters 
-Used bar chart, graphs to visualize 
-Created KPIs


<img width="1792" height="667" alt="Dashboard" src="https://github.com/user-attachments/assets/0f982e8b-8e1b-4404-9b6c-6e225ba658e4" />

## Insights
1.	Electronic category has the highest products.
2.	Most products are rated above average (most rating are between 4.0 – 4.3).
3.	Product with the highest rating fall under computer accessories category.
4.	Products with high rating have a high discount.
5.	Most Products price range are greater than ₹500.
6.	Customers Engagement by category does not directly depend on Discounts.
## Recommendation
1.	Home&Kitchen has potential so 
