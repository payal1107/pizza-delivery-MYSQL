# Pizza Sales Database Management System

## Project Overview

This project involves creating a MySQL database to manage and analyze pizza sales data. The focus is on customer orders, sales trends, and inventory management. The objective is to streamline sales data management and provide insights into sales trends, popular pizzas, and customer preferences.

## Table of Contents

1. [Introduction](#introduction)
2. [Database Design](#database-design)
3. [Database Schema](#database-schema)
4. [Key Queries & Codes](#key-queries--codes)
5. [Data Analysis & Conclusion](#data-analysis--conclusion)

## Introduction

This project is centered around building a MySQL database system to efficiently handle and analyze pizza sales data. The main goals are to track customer orders, identify sales patterns, and manage inventory more effectively.

## Database Design

### Entity Relationship (ER) Diagram

The ER diagram illustrates the relationships between four key tables:

- **Pizzas**: Contains details about individual pizzas, categorized by type.
- **Pizza_Types**: Stores information on different pizza types, including their categories and ingredients.
- **Orders**: Records each order placed by customers, including the date and time.
- **Order_Details**: Links specific pizzas to orders, detailing the quantity ordered.

This structure ensures efficient management of pizza sales data and facilitates easy tracking of sales trends and order details.

## Database Schema

The database schema is organized into four main tables:

1. **Pizzas**: `pizza_id`, `pizza_type_id`, `size`, `price`
2. **Pizza_Types**: `pizza_type_id`, `name`, `category`, `ingredients`
3. **Orders**: `order_id`, `order_date`, `order_time`
4. **Order_Details**: `order_details_id`, `order_id`, `pizza_id`, `quantity`

## Key Queries & Codes

### Key Insights and Queries:

1. **Total Orders**: Retrieve the total number of orders placed.
2. **Total Revenue**: Calculate the total revenue generated from pizza sales.
3. **Highest Priced Pizza**: Identify the most expensive pizza.
4. **Most Common Pizza Size**: Find the most frequently ordered pizza size.
5. **Top 5 Most Ordered Pizza Types**: List the top 5 pizza types and their quantities.
6. **Pizza Category Orders**: Join tables to find the total quantity of each pizza category ordered.
7. **Orders by Hour**: Analyze the distribution of orders by hour of the day.
8. **Category-Wise Pizza Distribution**: Find the distribution of pizzas by category.
9. **Average Pizzas Per Day**: Calculate the average number of pizzas ordered per day.
10. **Top 3 Pizzas by Revenue**: Determine the top 3 most ordered pizzas based on revenue.

## Data Analysis & Conclusion

### Data Analysis Summary:

- **Total Number of Orders**: 21,350
- **Total Revenue**: $817,860.05
- **Highest Priced Pizza**: The Greek Pizza at $35.95
- **Most Ordered Pizza Size**: Large (L)
- **Most Ordered Pizza**: The Classic Deluxe Pizza
- **Most Popular Pizza Category**: Classic
- **Peak Ordering Times**: 12:00 PM - 1:00 PM and 5:00 PM - 7:00 PM
- **Most Liked Pizza Type**: Chicken pizzas
- **Average Pizzas Ordered Per Day**: 138
- **Top 3 Ordered Pizzas**:
  1. The Thai Chicken Pizza
  2. The Barbecue Chicken Pizza
  3. The California Chicken Pizza

### Conclusion

- The MySQL database effectively manages and analyzes pizza sales data.
- The design captures critical information on pizzas, orders, and sales trends.
- SQL queries provided valuable insights into customer preferences and sales patterns.
- Future improvements may include adding customer feedback and real-time data analysis.
