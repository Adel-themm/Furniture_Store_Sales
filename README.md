# Furniture Store Sales Database Project

This project involves creating and managing a SQL database for a furniture store's sales data. It demonstrates the use of SQL for data management, storage, and simple transaction queries.

## Project Overview

The `furniture_store_sales` database was created to store and manage sales transactions, including product details, customer information, and payment types. This project can be extended for data analysis and visualization of sales trends and customer preferences.

## Database Details

### Database Name
- `furniture_store_sales`

### Table: `sales`
The main table, `sales`, stores the following fields:

| Column              | Data Type | Description                                     |
|---------------------|-----------|-------------------------------------------------|
| `ID`                | INTEGER   | Unique identifier for each transaction          |
| `transaction_date`  | TEXT      | Date and time of the transaction                |
| `product`           | TEXT      | Name of the product sold                        |
| `price`             | INTEGER   | Price of the product                            |
| `payment_type`      | TEXT      | Payment method used (e.g., Visa, Mastercard)   |
| `name`              | TEXT      | Customer's name                                 |
| `city`              | TEXT      | City of the customer                            |
| `state`             | TEXT      | State of the customer                           |
| `country`           | TEXT      | Country of the customer                         |
| `account_created`   | TEXT      | Date the customer's account was created         |
| `last_login`        | TEXT      | Last login date of the customer                 |
| `latitude`          | REAL      | Latitude of the customer’s location             |
| `longitude`         | REAL      | Longitude of the customer’s location            |

### Sample Data
Here is an example of inserting data into the `sales` table:

```sql
INSERT INTO sales(transaction_date, product, price, payment_type, name, city, state, country, account_created, last_login, latitude, longitude) 
VALUES ('1/2/09 6:17', 'Chair', 1200, 'Mastercard', 'Carolina', 'Basildon', 'England', 'United Kingdom', '1/2/09 6:00', '1/2/09 6:08', 51.5, -1.1166667);


