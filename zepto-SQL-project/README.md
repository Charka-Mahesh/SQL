
# Zepto SQL Data Analysis

📌 Project Summary

The dataset contains product-level attributes such as category, pricing, discounts, weight, and stock status.
The goal is to clean the data, understand product distribution, identify inconsistencies, and derive insights that can help in pricing, inventory, and category-level decisions.


---

📂 Dataset Fields

sku_id – Unique product ID

category – Product category

name – Product name

mrp – Maximum retail price

discountPercent – Discount offered

availableQuantity – Stock count

discountedSellingPrice – Final selling price

weightInGms – Weight

outOfStock – Availability status

quantity – Pack quantity



---

🧪 Data Exploration

Key exploration steps:

Count total records

View sample data

Detect null values

Identify unique categories

Compare in-stock vs out-of-stock items

Find duplicate product names



---

🧹 Data Cleaning

Removed products with mrp = 0

Converted prices from paise to rupees

Verified cleaned values

Checked for abnormal or inconsistent attributes



---

📊 Data Analysis Questions Answered

The project includes analytical queries such as:

1. Top 10 products with highest discount percentage

2. High-MRP items that are out of stock

3. Estimated revenue per category

4. Products with MRP > ₹500 and discount < 10%

5. Top 5 categories by average discount

6. Best-value products based on price per gram

7. Weight classification (Low / Medium / Bulk)

8. Total inventory weight per category


---

📁 How to Run

1. Import the SQL file into PostgreSQL or any SQL-compatible environment.


2. Create the table using the script.


3. Insert/load your dataset into the zepto table.


4. Run each query section to explore and analyze the data.




---

🎯 Skills Demonstrated

SQL Data Cleaning

Data Profiling

Joins, Aggregations, Window Logic

Business Insights for Retail/E-commerce

Analytical Thinking

