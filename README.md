# SupermarketPython

# Description

This is a supermarket system developed in Python, designed to manage customer, product, and shopping cart registrations, as well as handle the purchasing process. The system simulates a simple supermarket environment where customers can add products to the cart, check inventory, and complete purchases. It consists of classes to represent products, customers, carts, and the supermarket, as well as an interaction terminal for the user.

# Features

**1. Product Registration:**

The system allows new products to be added to the supermarket by specifying the name, price, and quantity available in stock.



**2. Customer Registration:**

Customers can be registered with personal information, such as name and CPF, to interact with the shopping system.

**3. Product Viewing:**

The administrator can view all products available in the supermarket, including details such as name, price, and stock quantity.

**4. Adding Products to Cart:**

Customers can add products to the cart by specifying the desired quantity. The system checks if there is sufficient stock for the requested amount and, if available, adds the product to the cart.

**5. Purchase Completion:**

When the customer decides to complete the purchase, the system calculates the total (based on products and quantities in the cart) and displays the final amount. After payment, the cart is emptied.

**6. Inventory Control:**

When a product is added to the cart, the stock quantity is automatically updated. The system prevents customers from adding more units than are available.

**7. Simple Text Interface:**

Interaction with the system is done through a command-line terminal, where the user can choose options like registering products, viewing inventory, and managing the shopping cart.

# Technologies Used

**Python:** Programming language used to develop the system.

**Object-Oriented Programming Concepts:** Use of classes to represent entities like products, customers, and shopping carts.

# How to Use

1. Clone the repository to your local machine.

2. Run the Python code in your terminal.

3. Follow the instructions in the terminal to interact with the system.

- Register products.

- Register customers.

- Add products to the cart.

- Complete purchases.

# Code Structure

The code is divided into several classes that represent system components:

**Product:** Represents a product in stock, with attributes like name, price, and available quantity.

**Customer:** Represents a customer, with methods to add products to the cart.

**Cart:** Represents the customer's shopping cart, calculating the total and managing products.

**Supermarket:** Controls the product inventory, manages customers, and processes purchases.

**Terminal:** Responsible for the user interface, providing an interactive menu of options.

# Possible Future Improvements

**Data Persistence:** Currently, data is lost when the program closes. Implementing a database solution or saving data to files would be a significant improvement.

**Graphical Interface:** For a more intuitive experience, a graphical interface using libraries like Tkinter or PyQt could be created.

**Validations and Errors:** Improve input validation, such as checking CPF formats and valid prices.

**Sales Reports:** Add functionalities to generate detailed sales reports, best-selling products, and low-stock alerts.


# Author

Erick Vinícius


