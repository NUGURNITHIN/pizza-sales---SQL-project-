The SQL-based pizza sales analysis project involves exploring and analyzing sales data for a pizza company using multiple datasets. The project covers sales trends, product performance, and customer preferences, helping the business make data-driven decisions. The datasets include:

Order Details (order_details.csv): This dataset contains information about each pizza sold, including the order ID, pizza type, and quantity.

Key Columns: order_id, pizza_id, quantity.
Orders (orders.csv): This dataset provides details about each order, including the order's timestamp.

Key Columns: order_id, date, time.
Pizza Types (pizza_types.csv): This dataset describes the pizza types, categories (e.g., Chicken, Veggie), and ingredients.

Key Columns: pizza_type_id, name, category, ingredients.
Pizzas (pizzas.csv): This dataset connects pizza types with their sizes and prices.

Key Columns: pizza_id, pizza_type_id, size, price.

Basic:
Retrieve the total number of orders placed.
Calculate the total revenue generated from pizza sales.
Identify the highest-priced pizza.
Identify the most common pizza size ordered.
List the top 5 most ordered pizza types along with their quantities.


Intermediate:
Join the necessary tables to find the total quantity of each pizza category ordered.
Determine the distribution of orders by hour of the day.
Join relevant tables to find the category-wise distribution of pizzas.
Group the orders by date and calculate the average number of pizzas ordered per day.
Determine the top 3 most ordered pizza types based on revenue.

Advanced:
Calculate the percentage contribution of each pizza type to total revenue.
Analyze the cumulative revenue generated over time.
Determine the top 3 most ordered pizza types based on revenue for each pizza category.
