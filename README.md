# Pizza Order Web App

This is a simple web application developed during a React course, where users can order one or more pizzas from a dynamic menu. The application includes the following features:

- No user accounts or logins are required.
- Users input their names before using the app.
- The pizza menu is loaded from an API, allowing for dynamic changes.
- Users can add multiple pizzas to a cart before placing an order.
- Ordering requires the user's name, phone number, and address.
- GPS location can be provided for easier delivery.
- Users can mark their order as "priority" for an additional 20% of the cart price.
- Orders are made by sending a POST request with the order data (user data + selected pizzas) to the API.
- Payments are made on delivery, so no payment processing is necessary within the app.
- Each order receives a unique ID, which is displayed to the user for order tracking.
- Users can mark their order as "priority" even after it has been placed.

