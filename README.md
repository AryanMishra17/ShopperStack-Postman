# ShopperStack Postman Collection Documentation

This document provides comprehensive documentation for the Postman collection designed for testing the ShopperStack e-commerce site.

## Endpoints Overview

### 1. Signup
- **Endpoint**: `/api/signup`
- **Method**: `POST`
- **Description**: Allows a new user to create an account.
- **Request Body**:
  - `email`: User's email address.
  - `password`: User's account password.

### 2. Login
- **Endpoint**: `/api/login`
- **Method**: `POST`
- **Description**: Authenticate a user and return a token.
- **Request Body**:
  - `email`: User's email address.
  - `password`: User's password.

### 3. Search Items
- **Endpoint**: `/api/items/search`
- **Method**: `GET`
- **Description**: Search for products based on a query.
- **Query Parameters**:
  - `query`: Search term for items.

### 4. Add to Cart
- **Endpoint**: `/api/cart/add`
- **Method**: `POST`
- **Description**: Adds a specified item to the user's cart.
- **Request Body**:
  - `item_id`: ID of the item to add.
  - `quantity`: Number of items to add.

### 5. Place Order
- **Endpoint**: `/api/order`
- **Method**: `POST`
- **Description**: Places an order for the items in the user's cart.
- **Request Body**:
  - `user_id`: ID of the user placing the order.

### 6. Remove from Cart
- **Endpoint**: `/api/cart/remove`
- **Method**: `POST`
- **Description**: Removes a specified item from the user's cart.
- **Request Body**:
  - `item_id`: ID of the item to remove.

### 7. Display All Items in Cart
- **Endpoint**: `/api/cart`
- **Method**: `GET`
- **Description**: Displays all the items currently in the user's cart.

## Conclusion

This documentation should provide a clear understanding of how to utilize the Postman collection for testing the ShopperStack e-commerce site.
### Screenshots

![Signup Screenshot]<img width="1920" height="1080" alt="signup" src="https://github.com/user-attachments/assets/6860bb27-9235-4cbb-96c5-e271d8444311" />

![Login Screenshot](path/to/login_screenshot.png)
![Search Items Screenshot](path/to/search_items_screenshot.png)
![Add to Cart Screenshot](path/to/add_to_cart_screenshot.png)
![Display Cart Screenshot](path/to/display_cart_screenshot.png)
![Place Order Screenshot](path/to/place_order_screenshot.png)
![Remove from Cart Screenshot](path/to/remove_from_cart_screenshot.png)
