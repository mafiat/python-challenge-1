# Variety Food Truck Menu Ordering System

This Python script simulates a menu ordering system for a variety food truck. Customers can select items from different categories, specify quantities, and receive a summary of their order.

## Menu Structure

The menu is organized into four main categories: Snacks, Meals, Drinks, and Dessert. Each category contains various items, some of which have sub-items.

### Example Menu

```python
menu = {
    "Snacks": {
        "Cookie": .99,
        "Banana": .69,
        "Apple": .49,
        "Granola bar": 1.99
    },
    "Meals": {
        "Burrito": 4.49,
        "Teriyaki Chicken": 9.99,
        "Sushi": 7.49,
        "Pad Thai": 6.99,
        "Pizza": {
            "Cheese": 8.99,
            "Pepperoni": 10.99,
            "Vegetarian": 9.99
        },
        "Burger": {
            "Chicken": 7.49,
            "Beef": 8.49
        }
    },
    "Drinks": {
        "Soda": {
            "Small": 1.99,
            "Medium": 2.49,
            "Large": 2.99
        },
        "Tea": {
            "Green": 2.49,
            "Thai iced": 3.99,
            "Irish breakfast": 2.49
        },
        "Coffee": {
            "Espresso": 2.99,
            "Flat white": 2.99,
            "Iced": 3.49
        }
    },
    "Dessert": {
        "Chocolate lava cake": 10.99,
        "Cheesecake": {
            "New York": 4.99,
            "Strawberry": 6.49
        },
        "Australian Pavlova": 9.99,
        "Rice pudding": 4.99,
        "Fried banana": 4.49
    }
}
```

## How to Use

1. **Launch the Script**: Run the script to start the ordering system.
2. **Select a Menu Category**: The script will prompt you to choose a category from the menu.
3. **Choose Items**: After selecting a category, you can choose items from that category and specify the quantity.
4. **Review Order**: Once you finish ordering, the script will display a summary of your order and the total cost.

## Example Output

```
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
Type menu item number: 1
How many Burrito would you like to order? 2
Would you like to keep ordering? (Y)es or (N)o N
Thank you for your order.
This is what we are preparing for you.

Item name                 | Price  | Quantity
--------------------------|--------|----------
Burrito                   | $4.49  | 2
```

## Features

- **Dynamic Menu**: Easily add or modify menu items and categories.
- **Order Summary**: Provides a clear summary of the customer's order.
- **Input Validation**: Ensures valid inputs for menu selection and quantities.

## Requirements

- Python 3.x

## Running the Script

To run the script, simply execute it in a Python environment:

```bash
python menu.py
```
