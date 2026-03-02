Day 2 – Queries and Filtering

Today, I focused on adding data and querying it. I used pgAdmin 4 again to insert customer records and retrieve them using SQL.

Key steps I took today:

Inserted customer data using the INSERT INTO statement.

Used the SELECT statement to view all customer records.

Applied the WHERE clause to filter customers by specific criteria (e.g., last name, email).

Ordered results using ORDER BY.

Sample SQL I wrote:

INSERT INTO customers (first_name, last_name, email, phone) 
VALUES 
('John', 'Doe', 'john.doe@email.com', '555-0101'),
('Jane', 'Smith', 'jane.smith@email.com', '555-0102');

SELECT * FROM customers;

SELECT * FROM customers WHERE last_name = 'Doe';

SELECT * FROM customers ORDER BY first_name;

I verified the queries by running them in the pgAdmin query tool and confirmed the results matched the expected data.
