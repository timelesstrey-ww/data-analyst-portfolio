# data-analyst-portfolio
My learning projects as a data analyst.
# My Data Analyst Journey
Hello! This is where I track all my projects and progress as I learn data analysis. Stay tuned as I add Python, SQL, and data visualization examples!
IBM Data Analyst Certificate
Issued by: IBM SkillsBuild
Date earned: September 2025
Credential URL: https://www.credly.com/badges/00040547-3978-4f2f-b8da-25e7c350c846/public_url
5 examples of 
1/5 -- Retrieve all columns and rows from the customers table
SELECT * FROM customers;
2/5 -- Get names and emails of customers from New York
SELECT name, email
FROM customers
WHERE city = 'New York';
3/5 -- List products sorted by price in descending order
SELECT product_name, price
FROM products
ORDER BY price DESC;
4/5 -- Find the number of orders and average order amount by customer
SELECT customer_id,
       COUNT(order_id) AS total_orders,
       AVG(order_total) AS avg_order_amount
FROM orders
GROUP BY customer_id;
5/5 -- Increase the price of all products in category "Electronics" by 10%
UPDATE products
SET price = price * 1.10
WHERE category = 'Electronics';
