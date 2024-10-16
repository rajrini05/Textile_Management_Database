# Textile_Management_Database
Project Description: Textile Management System

The Textile Management System is a database management project designed to streamline the operations of a textile retail business. This system is aimed at managing the key aspects of textile production, sales, inventory, and customer relations. It provides an efficient way to handle various functions such as tracking product details, managing customer orders, maintaining inventory levels, and generating sales reports. By utilizing a relational database management system (RDBMS), this project enables the storage, retrieval, and manipulation of data in an organized manner, ensuring that the business operates smoothly and effectively.

Key Objectives:
Inventory Management: Keep track of available textile products, including details like SKU, name, category, brand, price, and quantity.
Order Management: Manage customer orders, including order details such as customer information, order dates, quantities, and total prices.
Customer Relationship Management: Store and manage customer data to enhance sales strategies and customer service.
Sales Reporting: Generate reports to analyze sales performance, inventory turnover, and customer preferences.

Tables Overview
Products Table:

Description: Stores information about textile products.
Columns:
sku: Unique identifier for each product (Primary Key).
name: Name of the product.
category: Category of the product.
brand: Brand associated with the product.
price: Price of the product.
quantity: Available stock quantity.

Customers Table:

Description: Contains customer details.
Columns:

customer_id: Unique identifier for each customer (Primary Key).
customer_name: Name of the customer.
email: Customer's email address.
phone: Contact number.



Orders Table:

Description: Tracks orders made by customers.
Columns:
order_id: Unique identifier for each order (Primary Key).
customer_id: Reference to the customer placing the order (Foreign Key).
sku: Reference to the product being ordered (Foreign Key).
order_date: Date when the order was placed.
quantity: Number of items ordered.
total_price: Total cost of the order.


Creation of the Textile Management Database

The creation of the Textile Management Database involves a series of structured steps, encompassing planning, design, implementation, and testing. This process ensures that the database is robust, efficient, and capable of meeting the needs of the textile management system.

1. Planning Phase
Before creating the database, it is crucial to outline the objectives and requirements. During this phase, the following considerations are made:

Identify Users: Determine who will use the database, such as sales representatives, inventory managers, and customers.
Define Scope: Establish the features and functionalities required, including inventory tracking, order processing, and reporting.
Data Requirements: Identify the types of data that will be stored, such as product information, customer details, and order records.

2. Design Phase
Once the planning phase is complete, the next step is designing the database schema. This includes defining the tables, relationships, and constraints. The key components include:

Entity-Relationship Diagram (ERD): Create an ERD to visualize the entities (tables) and their relationships. The main entities for this project are Products, Customers, and Orders.
Define Tables: Each entity translates into a table with specific columns. For example:
Products Table: Stores product details such as SKU, name, category, brand, price, and quantity.
Customers Table: Contains customer information including customer ID, name, email, and phone number.
Orders Table: Tracks order data, including order ID, customer ID, SKU, order date, quantity, and total price.
ER -Diagram 


3. Implementation Phase

In this phase, the actual creation of the database and its tables occurs using SQL commands. Below is a step-by-step process for creating the database:
