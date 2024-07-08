# Music Store Analysis

## Overview

This project demonstrates advanced SQL query techniques to extract valuable insights from sales data in a music store. It includes multiple examples showcasing how to handle complex data transformations and aggregations using recursive queries, Common Table Expressions (CTEs), and window functions.

## Project Structure

### 1. Recursive Query for Single Visit Analysis

**Objective**: Identify customers who have visited a particular country only once and retrieve their details based on the highest value order.

**Methodology**:
- Data is sorted by country and purchase order value.
- The `ROW_NUMBER()` function is used to assign a unique number to each row within a partition.
- A recursive CTE filters out customers who visited the country only once.

### 2. Recursive Query for Maximum Purchase Value

**Objective**: Determine the maximum purchase value for each country and retrieve the customer details who made those purchases.

**Methodology**:
- Data is grouped by country, and the maximum purchase value for each country is calculated.
- The result is joined with customer details to identify the top spender in each country.

### 3. Recursive Query for Top Customers by Country

**Objective**: Identify the top customers by spending in each country and list their total spending.

**Methodology**:
- Total spending of each customer by country is aggregated.
- `ROW_NUMBER()` ranks customers based on their total spending within each country.
- The top customer for each country is filtered out.

## Conclusion

This project showcases the use of advanced SQL techniques to solve complex data queries for a music store's sales data. By using recursive queries, CTEs, and window functions, we can efficiently extract meaningful insights from large datasets. These examples demonstrate the power and flexibility of SQL in handling various data analysis scenarios.

## How to Run

1. **Database Setup**: Ensure you have a database with the necessary tables (`SalesData`, `Customers`).
2. **Load Data**: Insert sample data into these tables as per your requirements.
3. **Execute Queries**: Run the provided SQL queries in your SQL environment to get the desired outputs.

## Contact

For any queries or further assistance, please contact Aman Kumar Sharma.

---

This README now provides a comprehensive overview of the project, including objectives, methodologies, and how to run the queries, using all the parts of information you provided.## Overview

This project demonstrates advanced SQL query techniques to extract valuable insights from sales data in a music store. It includes multiple examples showcasing how to handle complex data transformations and aggregations using recursive queries, Common Table Expressions (CTEs), and window functions.

## Project Structure

### 1. Recursive Query for Single Visit Analysis

**Objective**: Identify customers who have visited a particular country only once and retrieve their details based on the highest value order.

**Methodology**:
- Data is sorted by country and purchase order value.
- The `ROW_NUMBER()` function is used to assign a unique number to each row within a partition.
- A recursive CTE filters out customers who visited the country only once.

### 2. Recursive Query for Maximum Purchase Value

**Objective**: Determine the maximum purchase value for each country and retrieve the customer details who made those purchases.

**Methodology**:
- Data is grouped by country, and the maximum purchase value for each country is calculated.
- The result is joined with customer details to identify the top spender in each country.

### 3. Recursive Query for Top Customers by Country

**Objective**: Identify the top customers by spending in each country and list their total spending.

**Methodology**:
- Total spending of each customer by country is aggregated.
- `ROW_NUMBER()` ranks customers based on their total spending within each country.
- The top customer for each country is filtered out.

## Conclusion

This project showcases the use of advanced SQL techniques to solve complex data queries for a music store's sales data. By using recursive queries, CTEs, and window functions, we can efficiently extract meaningful insights from large datasets. These examples demonstrate the power and flexibility of SQL in handling various data analysis scenarios.

## How to Run

1. **Database Setup**: Ensure you have a database with the necessary tables (`SalesData`, `Customers`).
2. **Load Data**: Insert sample data into these tables as per your requirements.
3. **Execute Queries**: Run the provided SQL queries in your SQL environment to get the desired outputs.

## Contact

aamansharma027@gmail.com

---

This README now provides a comprehensive overview of the project, including objectives, methodologies, and how to run the queries, using all the parts of information you provided.
