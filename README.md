# Matcha Shop SQL Analysis:  
This is a SQL project analysing sales data for a fictional Matcha Shop/Café.  
Built using PostgreSQL, pgAdmin, and structured for a professional GitHub portfolio.



## Project Overview: 
This project demonstrates SQL skills that are commonly used in Data Analyst and Business Analyst roles such as:

- Database schema design  
- Data cleaning and importing CSVs  
- Writing analytical SQL queries  
- Calculating business KPIs and insights  
- Making a clear project repo with data + SQL files  

The dataset includes:
- 10 customers
- 8 products
- 60 orders
- 122 order items

All data is over June–August 2025.



## Project Structure:
```
matcha-shop-sql-analysis/
│
├── data/ <- CSV files imported into PostgreSQL
│ ├── matcha_customers.csv
│ ├── matcha_products.csv
│ ├── matcha_orders.csv
│ └── matcha_order_items.csv
│
├── sql/ <- SQL scripts
│ ├── create_tables.sql
│ └── analysis_queries.sql
│
└── README.md <- Project documentation
```


## Database Schema:

**Tables created:**
- `customers`
- `products`
- `orders`
- `order_items`

Each table is linked using foreign keys (e.g., orders → customers, order_items → products).



## Key Business Insights (KPIs):

### Total revenue:  
$1,487.72

### Total orders:  
60 orders

### Average order value:  
$24.80

### Monthly revenue:  
- June: $497 
- July: $535
- August: $455

### Top products by revenue:  
- Ceremonial Matcha 30g Tin: $693
- Matcha Latte: $169.95
- Matcha Brownie: $159.20

### Repeat customer rate:  
100% (all customers made multiple orders)

### Top customers:  
- Daniel Kim: $349
- Emma Jones: $241 
- Aisha Patel: $183



## SQL Techniques Used:  
- Common Table Expressions (CTEs)  
- Window functions (`RANK()`)  
- Aggregate functions (`SUM`, `AVG`, `COUNT`)  
- Date truncation and grouping  
- Joins across multiple tables  
- Data modelling and schema creation  



## Future Improvements:  
- Interactive Power BI dashboard connected directly to PostgreSQL  
- Profit margin calculations  
- Predictive analytics (forecasting monthly sales)  
- Analysing customer habits



## Author:  
**Shruti Baleri**  
BSc. Economics student and aspiring Data Analyst  
