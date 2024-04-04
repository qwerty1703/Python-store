# Python-store

This Python project implements a simple shopping management system with both admin and user functionalities. Here's a brief description of the project:

### Features:

1. **Admin Functions:**
   - Display Menu: View the list of products available for sale.
   - Add Product: Add new products to the inventory.
   - Remove Product: Remove existing products from the inventory.
   - Products Available: Display the current availability of each product.
   - Total Income: Calculate and display the total income generated from sales.
   - Logout: Exit from the admin panel.

2. **User Functions:**
   - Display Menu: View the list of products available for purchase.
   - Place Order: Select a product and place an order.
   - Cancel Order: Cancel a previously placed order.
   - Logout: Exit from the user panel.

### Workflow:

1. **Admin Login:**
   - The admin can log in by providing the correct password.
   - Upon successful login, the admin can access the admin panel to perform various tasks.

2. **Admin Tasks:**
   - The admin can perform actions such as displaying the menu, adding or removing products, checking product availability, and viewing total income.
   - Each task is executed by selecting the corresponding option from the menu.

3. **User Login:**
   - Users can log in by providing the correct password.
   - Upon successful login, users can access the user panel to browse products and place orders.

4. **User Tasks:**
   - Users can view the list of available products, select a product to purchase, and place orders.
   - They can also cancel orders if needed.

### Implementation Details:

- The project uses dictionaries to represent product details such as ID, name, availability, price, and original price.
- Functions are implemented for each task, making the code modular and easy to maintain.
- Both admin and user interfaces are provided with separate functionalities and options.
- Input validation is implemented to handle incorrect user inputs.

### Usage:

- Users can interact with the system through a command-line interface.
- Admins can manage the inventory, while users can browse products and place orders.

