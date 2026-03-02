Day-01-Database-Basics/notes.md
Day 1 – Database Basics

Today I learned about:

What a database is.

How to create a database.

How to create tables with SQL.

I used pgAdmin 4 as my database management tool. After installing PostgreSQL and pgAdmin 4, I created a new database by connecting to my local server. Using the query tool, I ran the following SQL to create my customer table:

CREATE TABLE customers (
    customer_id SERIAL PRIMARY KEY,
    first_name VARCHAR(50) NOT NULL,
    last_name VARCHAR(50) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL,
    phone VARCHAR(15),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

I verified the table creation by selecting the table in the GUI and running a simple SELECT query to confirm the structure. pgAdmin’s graphical interface helped me visualize the database schema and ensure all columns were set up correctly.
