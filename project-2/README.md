# Instacart Project

For this project, I'll be working with data from Instacart. 

Instacart is a grocery delivery platform where customers can place a grocery order and have it delivered to them, similar to how Uber Eats and Door Dash work. This particular dataset was publicly released by Instacart in 2017 for a Kaggle competition. However, since the original dataset was no longer available on the Instacart website, I'll be working on a modified version of the data.

# Goal
My goal is to clean up the data and prepare a report that gives insight into the shopping habits of Instacart customers. I'll be answering questions, and then write a brief explanation of the results in the Jupyter notebook.

# Data Dictionary
There are five tables in the dataset that I will be using for data preprocessing and EDA. Below is a data dictionary that lists the columns in each table and describes that data that hold.

- instacart_orders.csv: each row corresponds to one order on the Instacart app
  - 'order_id': ID number that uniquely identifies each order
  - 'user_id': ID number that uniquely identifies each customer account
  - 'order_number': the number of times this customer has placed an order
  - 'order_dow': day of the week that the order placed (which day is 0 is uncertain)
  - 'order_hour_of_day': hour of the day that the order was placed
  - 'days_since_prior_order': number of days since this customer placed their previous order

- products.csv: each row corresponds to a unique product that customers can buy
  - 'product_id': ID number that uniquely identifies each product
  - 'product_name': name of the product
  - 'aisle_id': ID number that uniquely identifies each grocery aisle category
  - 'department_id': ID number that uniquely identifies each grocery department category

- order_products.csv: each row corresponds to one item placed in an order
  - 'order_id': ID number that uniquely identifies each order
  - 'product_id': ID number that uniquely identifies each product
  - 'add_to_cart_order': the sequential order in which each item was placed in the cart
  - 'reordered': 0 if the customer has never ordered this product before, 1 if they have

- aisles.csv
  - 'aisle_id': ID number that uniquely identifies each grocery aisle category
  - 'aisle': name of the aisle

- departments.csv
  - 'department_id': ID number that uniquely identifies each grocery department category
  - 'department': name of the department
 
# Libraries
- Pandas
