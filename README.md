# Sales-Reporting-System
 A data analysis project focused on customers, products, and orders using PostgreSQL for database creation and SQL queries. Visualized insights with Power BI to support sales reporting and business decision-making.
## Problem Statement
 Businesses frequently find it challenging to extract actionable insights from disjointed sales data. This project offers a streamlined system for analyzing customer behavior, product performance, and order trends, facilitating informed decision-making.
## Tools Used
- **PostgreSQL** – For database creation and querying
- **Power BI** – For interactive data visualizations -
- **SQL** – For data extraction, transformation, and aggregation
## Skills Demonstrated
(i) ***combining tables to show customer name and products***
```bash
select customer_name, product_name 
from customers
inner join orders
on customers.customer_id = orders.customer_id
inner join products
on products.product_id = orders.product_id
```
![customer_product](customer_by_product.png)


