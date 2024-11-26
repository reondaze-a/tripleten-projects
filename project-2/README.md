# Instacart Project
[Project Notebook](https://github.com/reondaze-a/tripleten-projects/blob/main/project-2/instacart_project.ipynb)
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

# Analysis questions
These are the questions that I will be working on answering through the data analysis:


1. Verify that values in the 'order_hour_of_day' and 'order_dow' columns in the orders table are sensible (i.e. 'order_hour_of_day' ranges from 0 to 23 and 'order_dow' ranges from 0 to 6).
2. Create a plot that shows how many people place orders for each hour of the day.
3. Create a plot that shows what day of the week people shop for groceries.
4. Create a plot that shows how long people wait until placing their next order, and comment on the minimum and maximum values.
5. Is there a difference in 'order_hour_of_day' distributions on Wednesdays and Saturdays? Plot the histograms for both days on the same plot and describe the differences that you see.
6. Plot the distribution for the number of orders that customers place (e.g. how many customers placed only 1 order, how many placed only 2, how many only 3, and so on…)
7. What are the top 20 products that are ordered most frequently (display their id and name)?
8. How many items do people typically buy in one order? What does the distribution look like?
9. What are the top 20 items that are reordered most frequently (display their names and product IDs)?
10. For each product, what proportion of its orders are reorders (create a table with columns for the product ID, product name, and reorder proportion)?
11. For each customer, what proportion of their products ordered are reorders?
12. What are the top 20 items that people put in their carts first (display the product IDs, product names, and number of times they were the first item added to the cart)?
