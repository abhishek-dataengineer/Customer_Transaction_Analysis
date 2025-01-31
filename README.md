# Customer_Transaction_Analysis
-------------------------------
This project involves analyzing customer transactions for an e-commerce business using PostgreSQL. The goal is to extract meaningful insights about customer behavior, revenue trends, and purchasing patterns using SQL queries.

Key Analysis Areas & SQL Techniques Used:
------------------------------------------
1. Basic Business Insights (SQL Aggregation & Filtering)

2. Intermediate Analysis (Subqueries & Aggregation)
Determined the customer with the highest total spend.
Analyzed the most popular payment method.
Identified customers who spent more than the average.
Found which product category contributed the most revenue.
Calculated the percentage of transactions with discounts applied.
Example Query - Finding the Most Popular Payment Method:

3. Advanced Analysis (Window Functions, CTEs, & Lead/Lag Analysis)
Ranked customers based on total spending using window functions.
Found the first and last purchase date for each customer using CTEs and window functions.
Used LEAD() to determine the gap between customer purchases.
Created a monthly revenue trend analysis to identify business growth patterns.
Found inactive customers who haven’t made a purchase in the last 6 months.
Example Query - Monthly Revenue Trend Using CTE:




Key Takeaways:
----------------
Used SQL subqueries, CTEs, and window functions to perform in-depth customer transaction analysis.

Built a structured PostgreSQL database to store and query e-commerce transaction data.

Discovered actionable business insights like customer retention trends, revenue forecasting, and discount impact on sales.

Improved data-driven decision-making for customer engagement strategies.



How to Present This in an Interview:
-------------------------------------
When asked about your SQL skills, you can say:
"In my recent project, I worked on analyzing customer transactions using PostgreSQL. I started with basic queries for revenue tracking and customer behavior analysis. Then, I incorporated subqueries and window functions to rank customers, analyze purchase frequency, and track retention trends. Additionally, I used CTEs and LAG/LEAD functions to compare monthly revenue changes and identify customer inactivity patterns. This project helped me gain a deep understanding of SQL for business intelligence and analytics."
