#  DSA- Amazon Product Review Analysis (RetailTech Insights) Case study

## Business Introduction 
RetailTech Insights is a company that provides E-commerce analytics solutions to sellers on platforms like Amazon. 

## Project Objective 
The aim of this project is to analyze product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement. This was done by answering these following business questions:
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

Total Records: 1,465 rows.
Total Fields: 16 columns.

## Tool
   -Microsoft Excel 
  
   -Excel Pivot tables 
  
   -Excel Pivot Charts

## Process 
#### Step 1: Data Cleaning and transformation
-Removal of duplicates using ProductID, ReviewID and userID.

-Converting data format to the appropriate format.

-Breaking categories into subcategories for better summarization using delimiter.

-Trimming product name 

#### Step 2: Data Analysis:
-Calculated Columns: calculation of Revenuw, generating price bucket 

-Pivot tables: For summarization (Average, Counts..).

-Sorting/Filtering:Identification top products by rating and review. 

#### Step 3: Data Visualization 
-Visualization using bar charts, pie chart and graphs

-Built Interactive Dashboard using Slicers


<img width="1792" height="667" alt="Dashboard" src="https://github.com/user-attachments/assets/0f982e8b-8e1b-4404-9b6c-6e225ba658e4" />

## Insights
1.	Electronic category has the highest products.
2.	Most products are rated above average, with majority falling between 4.0 to 4.3
3.	Product with the highest rating fall under computer accessories category.
4.	Products with high rating have a high discount.
5.	Most Products price range are above ₹500.
6.	Customers Engagement by category does not directly depend and correlate with Discounts.
   
## Recommendation
-Scale the Computer Accessories category it shows strong customer satisfaction.

-Use customer reviews to identify complaints for product improvement.

-Introduce combo deals in order to boost low performing products.



Check file for clearer picture of visualization.


