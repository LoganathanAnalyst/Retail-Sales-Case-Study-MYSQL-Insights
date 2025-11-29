
🛒 Retail Sales Analysis — SQL Case Study

------------------------------------------
📌 Project Overview  
This project explores a Retail Sales dataset using SQL, focusing on sales performance, customer behavior, product trends, and revenue patterns.

🗄️ Database Structure  
Tables Used:
1. sales – transaction details (date, product, quantity, total amount)
2. customers – customer information
3. products – product names, categories, and pricing

------------------------------------------

🎯 Key Objectives

🛍️ Sales Exploration:
- 📊 Total sales & revenue
- 👥 Unique customers
- ⭐ Best & worst selling products
- 🗂️ Category-wise performance
- 💵 Average order value (AOV)

👤 Customer Analysis:
- 🔁 Repeat vs new customers
- 💰 Highest spending customers
- ⏱️ Purchase frequency patterns

📦 Product Trends:
- 💸 Most profitable categories
- 🏷️ Price distribution
- 📆 Monthly/seasonal sales trends

🔗 Combined Insights:
- 🤝 Joining tables for deeper insights
- 🧾 High-value orders
- 📂 Revenue contribution by category
- 🧺 Top-product basket analysis

------------------------------------------

🧪 Sample Query — Top 5 Products by Revenue

SELECT 
    product_name,
    SUM(total_amount) AS total_revenue
FROM sales
GROUP BY product_name
ORDER BY total_revenue DESC
LIMIT 5;

------------------------------------------

🧠 Skills Demonstrated
- 🔢 Aggregations
- 🔗 Joins
- 🔍 Filtering
- 📚 Subqueries
- 🪟 Window Functions
- 🕒 Time-based Analysis
- 🔎 Exploratory SQL
- 📊 Real business analysis
------------------------------------------

Badges:
![SQL](https://img.shields.io/badge/SQL-Analysis-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Compatible-316192?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Compatible-4479A1?logo=mysql&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-SQL-green)
![License](https://img.shields.io/badge/Status-Active-success)

------------------------------------------

🤝 Contributing Have ideas to improve this dashboard? Feel free to open issues or submit pull requests.

⭐ Support This Project

If you found this dashboard useful, please star ⭐ the repository. Your support motivates further improvements!

👨‍💻 About the Author
Hi, I’m Loganathan, a Data Analyst & Power BI Developer passionate about transforming data into meaningful insights.
Thank you for exploring this project — Happy Learning! 🎉📚

📬 Contact  
For collaboration or questions: your-loganathanvizasia@gmail.com




