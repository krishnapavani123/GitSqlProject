Zomato Sales Analysis Project
Overview
The Zomato Sales Analysis project provides an in-depth analysis of Zomato's sales data.
This project aims to derive valuable insights into customer behavior, product performance, and overall business strategies using SQL queries.
By examining purchase patterns, customer preferences, and product popularity,
the project helps to identify areas for improvement in customer engagement, marketing strategies, and product offerings.

# Database Structure
The database consists of four primary tables:

1.goldusers_signup: This table records users who signed up for Zomato's premium gold membership, including the date of signup.

Columns: userid (integer), gold_signup_date (date)

2.users: Contains details of Zomato users, including their signup date.

Columns: userid (integer), signup_date (date)

3.product: A list of products available for purchase on Zomato, including their ID, name, and price.

Columns: product_id (integer), product_name (text), price (integer)

4.sales: Records the sales transactions, linking users to products they purchased and the date of purchase.

Columns: userid (integer), created_date (date), product_id (integer)

# Setup Instructions
Prerequisites
MySQL or any compatible database.

SQL client (e.g., MySQL Workbench, DBeaver) for executing the queries.

Running the Queries
Clone the repository:

git clone https://github.com/krishnapavani123/GitSqlProject.git
Import the provided SQL files into your database.

Run each SQL query within your SQL client to analyze the data and retrieve insights.

# Conclusion
This project demonstrates expertise in data analysis and SQL integration by providing actionable insights into Zomato's operations.
By analyzing user behavior, product sales, and revenue trends, the project helps guide strategic decision-making.
It showcases a deep understanding of SQL and business analytics and provides meaningful recommendations for improving customer engagement and product offerings.
