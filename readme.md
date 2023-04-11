<!DOCTYPE html>
<html>
<head>
    <title>Grocery Delivery App</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS file -->
</head>
<body>
    <header>
        <h1>Grocery Delivery App</h1>
    </header>
    <main>
        <section id="grocery-list">
            <h2>Grocery List</h2>
            <ul id="groceries">
                <li>Apples</li>
                <li>Bananas</li>
                <li>Cheese</li>
                <li>Bread</li>
                <li>Eggs</li>
            </ul>
        </section>
        <section id="delivery-address">
            <h2>Delivery Address</h2>
            <form id="address-form" action="checkout.html" method="post"> <!-- Form for delivery address -->
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="address">Address:</label>
                <input type="text" id="address" name="address" required>
                <label for="phone">Phone:</label>
                <input type="text" id="phone" name="phone" required>
                <input type="submit" value="Checkout">
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Grocery Delivery App. All rights reserved.</p>
    </footer>
    <script src="script.js"></script> <!-- Link to external JavaScript file -->
</body>
</html>
