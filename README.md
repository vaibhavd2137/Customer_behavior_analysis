# Customer_behavior_analysis
Data analytics Project using Python,MySql,PowerBi
 Customer Shopping Behavior Analysis
A complete end-to-end data analytics project exploring customer shopping behavior using Python, MySQL, and Power BI. The goal is to understand spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.
1. Overview
This project analyzes 3,900 customer transactions containing demographic details, purchase patterns, product choices, and shopping behavior.
The workflow includes:
•	Data loading & preprocessing (Python)
•	Exploratory Data Analysis (EDA)
•	SQL-based business analysis
•	Interactive Power BI dashboard

2. Dataset Summary
Rows: 3,900
Columns: 18
Key Features:
•	Demographics: Age, Gender, Location, Subscription Status
•	Purchase Details: Item, Category, Season, Size, Color, Purchase Amount
•	Behavior: Discount Applied, Promo Code Used, Previous Purchases, Review Rating, Shipping Type
•	Missing Values: 37 missing in Review Rating → imputed using category-wise median

3. Tools & Technologies
Stage	Tools
Data Cleaning 
& EDA	Python, Pandas, NumPy, Matplotlib/Seaborn
Database Analysis	  MySQL
Visualization	Power BI
Documentation	MS Word / PDF
Presentation	MS PowerPoint

4. Project Workflow
A. Python – Data Cleaning & EDA
•	Loaded dataset using Pandas
•	Inspected structure using .info() and .describe()
•	Imputed missing Review Rating values
•	Standardized column names (snake_case)
•	Feature engineering:
o	age_group (binned ages)
o	purchase_frequency_days
•	Removed redundant columns such as promo_code_used
•	Connected cleaned data to MySQL for deeper analytics
________________________________________
B. SQL – Business Analysis
Using MySQL, several business-focused questions were answered:
✔ Revenue by gender
✔ High-spending customers using discounts
✔ Top 5 products by average rating
✔ Standard vs express shipping spend comparison
✔ Subscriber vs non-subscriber revenue
✔ Top products per category
✔ Discount-dependent products
✔ Customer segmentation (New, Returning, Loyal)
✔ Repeat buyers’ subscription likelihood
✔ Revenue contribution by age group
________________________________________
C. Power BI – Interactive Dashboard
The dashboard provides:
•	KPI Cards: Avg rating, Avg purchase amount, Total customers
•	Pie chart: Subscription status distribution
•	Bar charts:
o	Revenue by Age Group
o	Revenue by Category
o	Sales by Category
•	Filters for Gender, Category, Season, and Shipping Type
•	User-friendly UI with clear visual storytelling

 5. Key Insights
Some of the major findings:
•	Young Adults contribute the highest revenue
•	Subscribers spend more than non-subscribers
•	Many products are discount-dependent
•	Clothing & Accessories have the highest volume
•	Express shipping correlates with higher purchase amounts
•	Top-rated products were mostly in Accessories & Clothing

