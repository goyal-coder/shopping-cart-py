Overview
This is a simple restaurant ordering system written in Python. It allows users to order food from a predefined menu, calculates the total price dynamically, and stops when the user decides to quit.

Features
✅ Displays a menu with food items and prices.
✅ Takes user input for ordering food.
✅ Stores the ordered items in a list.
✅ Calculates and updates the total price after each order.
✅ Allows users to quit the ordering process by entering "q".

How It Works
The script starts by defining two lists:

foods: Stores the names of available food items.
prices: Stores the corresponding prices of each item.
The menu is displayed using a loop.

A while loop keeps asking the user to enter a food item to order.

If the user enters "q", the loop breaks and stops ordering.
Otherwise, the program adds the selected food to user_order, finds its price, updates total, and displays the updated total.
Potential Improvements
🔹 Add error handling to check if the user enters an invalid food name.
🔹 Allow users to order multiple quantities of the same food.
🔹 Format the prices to two decimal places for better readability.
🔹 Display the final order summary before exiting.

This basic restaurant ordering system can be expanded into a more complex food ordering app with additional features like payment processing, discounts, or delivery options. 🚀
