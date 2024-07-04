
🛒 Supermarket Billing System 🛍️

The supermarket billing system in Java is designed to manage the billing process efficiently. Here's an overview of its core components and functionalities:

    Product Class 📦:
        Attributes: Contains product ID, name, price, and quantity.
        Methods:
            getProductDetails(): Retrieves product information.
            updateQuantity(): Updates the quantity of a product.

    Cart Class 🛒:
        Attributes: A list to store products added to the cart.
        Methods:
            addProduct(Product product): Adds a product to the cart.
            removeProduct(Product product): Removes a product from the cart.
            calculateTotal(): Calculates the total price of the items in the cart.

    Billing Class 💰:
        Attributes: Cart object and total amount.
        Methods:
            generateBill(): Generates the final bill showing product details and total amount.
            printBill(): Prints the bill.

    Main Class 🚀:
        Methods:
            main(String[] args): The entry point of the application. It initializes products, adds them to the cart, and generates the bill.


