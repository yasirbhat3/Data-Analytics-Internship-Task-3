Data Analyst Internship – Task 3

 Author  
Yasir Bilal Bhat

Task  
SQL Basics – Filtering, Sorting & Aggregations

 Tools  
MySQL / PostgreSQL, SQLite Online, DB Fiddle

 Work Done  
- Created database and tables  
- Imported dataset into SQL  
- Used SELECT, WHERE, ORDER BY  
- Applied GROUP BY, HAVING  
- Used SUM, AVG, COUNT  
- Wrote professional SQL queries  
- Added interview Q&A  

 Sample Query  
```sql
SELECT Customer_Name, SUM(Sales) AS Total_Spend
FROM sales_data
GROUP BY Customer_Name
ORDER BY Total_Spend DESC
LIMIT 5;# Data-Analytics-Internship-Task-3
Data Analyst Internship Task 3 – SQL basics with filtering, sorting, aggregation &amp; documentation.
