# Food Truck Order System

This project is a menu-based order system for a food truck. It allows customers to place orders from a variety of categories, including snacks, meals, drinks, and desserts. The system stores the orders, calculates the total price, and prints a receipt for the customer.

## Features

- Display menu categories and items with prices
- Allow customers to select items and specify quantities
- Validate user inputs for menu selection and quantities
- Store customer orders in a list
- Print a detailed receipt with the total price

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository (if applicable) or download the `order_system.py` file to your local machine.

```bash
git clone <repository_url>
cd <repository_directory>

python order_system.py

Welcome to the variety food truck.
From which menu would you like to order? 
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 2
You selected Meals
What Meals item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
4      | Pad Thai                 | $6.99
5      | Pizza - Cheese           | $8.99
6      | Pizza - Pepperoni        | $10.99
7      | Pizza - Vegetarian       | $9.99
8      | Burger - Chicken         | $7.49
9      | Burger - Beef            | $8.49
Please enter the menu item number you would like to order: 1
How many Burritos would you like to order? (default is 1): 2
2 Burrito(s) added to your order.
Would you like to keep ordering? (Y)es or (N)o y
...

This is what we are preparing for you.

Item name                 | Price  | Quantity
--------------------------|--------|----------
Burrito                   | $4.49  | 2
--------------------------|--------|----------
Total price: $8.98

