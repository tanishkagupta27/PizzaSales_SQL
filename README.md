# PizzaSales_SQL
# Overview

This project involves analyzing a dataset of pizza orders stored in a relational database. The goal is to answer several business questions using SQL queries:


~ Retrieve the total number of orders placed.

~ Calculate the total revenue generated from pizza sales.

~ Identify the highest-priced pizza.

~ Identify the most common pizza size ordered.

~ List the top 5 most ordered pizza types along with their quantities.



# Purpose


This analysis is designed to provide insights into pizza sales data. By querying the database, we can answer key business questions that can help with sales strategy, inventory management, and customer preferences.



# Database Schema

The analysis assumes the following database schema:



# orders table


Column Name	Type	Description

- order_id	INT	Unique ID for each order

- order_date	DATE	Date the order was placed



# order_items table


Column Name	Type	Description

- item_id	INT	Unique ID for each item in the order

- order_id	INT	Foreign key to the orders table

- pizza_type	TEXT	Type of pizza ordered (e.g., Margherita, Pepperoni)

- price	INT	Price of the pizza

- quantity	INT	Quantity of the pizza ordered



## Example Data


The database contains the following tables:

- orders: Contains general order details.

- order_items: Contains details of the pizzas in each order.
