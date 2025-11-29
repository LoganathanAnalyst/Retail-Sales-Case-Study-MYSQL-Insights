
🛒 Retail Sales Analysis — SQL Case Study

Project Overview
This project explores a Retail Sales dataset using SQL, focusing on sales performance, customer behavior, product trends, and revenue patterns.

Database Structure
Tables Used:
1. sales – transaction details (date, product, quantity, total amount)
2. customers – customer information
3. products – product names, categories, and pricing

Key Objectives
Sales Exploration:
- Total sales & revenue
- Unique customers
- Best & worst selling products
- Category-wise performance
- Average order value (AOV)

Customer Analysis:
- Repeat vs new customers
- Highest spending customers
- Purchase frequency patterns

Product Trends:
- Most profitable categories
- Price distribution
- Monthly/seasonal sales trends

Combined Insights:
- Joining tables for deep insights
- High-value orders
- Revenue contribution by category
- Top-product basket analysis

Sample Query — Top 5 Products by Revenue
SELECT 
    product_name,
    SUM(total_amount) AS total_revenue
FROM sales
GROUP BY product_name
ORDER BY total_revenue DESC
LIMIT 5;

Skills Demonstrated
- Aggregations
- Joins
- Filtering
- Subqueries
- Window Functions
- Time-based Analysis
- Exploratory SQL
- Real business analysis

Contact
For collaboration or questions: your-email@example.com


