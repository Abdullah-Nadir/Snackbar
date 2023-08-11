
# Snackbar

# Learning Goals

- Practice using structs
- Write a linear search algorithm
## Background

Imagine you’re at the beach and want to order a number of items from the snack bar. You have a limited amount of cash on you, and you want to get a total cost for your items before ordering. In `snackbar.c` there are two functions. First is add_items which will add at least the items available on the Beach Burger Shack menu. Then the second function get_cost which will implement a linear search algorithm to search for each item you choose, and return the corresponding price.


## Implementation Details

In main function after calling add_items to initialize the menu array, it will print out the menu items and their prices, prompting you to keep selecting items until you press enter without typing anything in. There are two functions, add_items, which adds at least the menu items, and get_cost to return the cost of each item. The linear search algorithm in get_cost, is case insentive.

## Usage/Examples

```javascript
snackbar/ $ ./snackbar

Welcome to Beach Burger Shack!
Choose from the following menu to order. Press enter when done.

Burger: $9.50
Vegan Burger: $11.00
Hot Dog: $5.00
Cheese Dog: $7.00
Fries: $5.00
Cheese Fries: $6.00
Cold Pressed Juice: $7.00
Cold Brew: $3.00
Water: $2.00
Soda: $2.00

Enter a food item: burger
Enter a food item: fries
Enter a food item: soda
Enter a food item: 

Your total cost is: $16.50
```

```javascript
snackbar/ $ ./snackbar

Welcome to Beach Burger Shack!
Choose from the following menu to order. Press enter when done.

Burger: $9.50
Vegan Burger: $11.00
Hot Dog: $5.00
Cheese Dog: $7.00
Fries: $5.00
Cheese Fries: $6.00
Cold Pressed Juice: $7.00
Cold Brew: $3.00
Water: $2.00
Soda: $2.00

Enter a food item: cold brew
Enter a food item: hot dog
Enter a food item: 

Your total cost is: $8.00
```
