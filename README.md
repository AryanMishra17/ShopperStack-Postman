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
[Signup Screenshot]<img width="1920" height="1080" alt="signup" src="https://github.com/user-attachments/assets/6860bb27-9235-4cbb-96c5-e271d8444311" />


### 2. Login
- **Endpoint**: `/api/login`
- **Method**: `POST`
- **Description**: Authenticate a user and return a token.
- **Request Body**:
  - `email`: User's email address.
  - `password`: User's password.

[Login Screenshot]
<img width="1920" height="1080" alt="login" src="https://github.com/user-attachments/assets/650235e8-9cd1-47bf-a3dc-1314e56298fb" />



### 3. Search Items
- **Endpoint**: `/api/items/search`
- **Method**: `GET`
- **Description**: Search for products based on a query.
- **Query Parameters**:
  - `query`: Search term for items.
 
[Search Items Screenshot]
<img width="1920" height="1080" alt="search item" src="https://github.com/user-attachments/assets/c6834047-8da6-4d57-8f47-8ed2386dc353" />


### 4. Add to Cart
- **Endpoint**: `/api/cart/add`
- **Method**: `POST`
- **Description**: Adds a specified item to the user's cart.
- **Request Body**:
  - `item_id`: ID of the item to add.
  - `quantity`: Number of items to add.

[Add to Cart Screenshot]
<img width="1920" height="1080" alt="add to cart 2" src="https://github.com/user-attachments/assets/0aaee7ca-44d7-46a2-9fe8-e841afa4989d" />
<img width="1920" height="1080" alt="added to cart" src="https://github.com/user-attachments/assets/45e7dcfb-a39d-4d5e-a3df-dd35cb8ed105" />



### 5. Place Order
- **Endpoint**: `/api/order`
- **Method**: `POST`
- **Description**: Places an order for the items in the user's cart.
- **Request Body**:
  - `user_id`: ID of the user placing the order.

[Place Order Screenshot]
<img width="1920" height="1080" alt="placed order" src="https://github.com/user-attachments/assets/6658fc76-c79e-475b-b882-b032751f38c7" />
<img width="1920" height="1080" alt="placed order from postman" src="https://github.com/user-attachments/assets/33289fda-f433-4bba-8ff9-203115122b01" />


### 6. Remove from Cart
- **Endpoint**: `/api/cart/remove`
- **Method**: `POST`
- **Description**: Removes a specified item from the user's cart.
- **Request Body**:
  - `item_id`: ID of the item to remove.
[Remove from Cart Screenshot]
<img width="1920" height="1080" alt="remove from cart" src="https://github.com/user-attachments/assets/c8599395-19cd-4e29-b075-6a8a7bf52567" />



### 7. Display All Items in Cart
- **Endpoint**: `/api/cart`
- **Method**: `GET`
- **Description**: Displays all the items currently in the user's cart.

[Display Cart Screenshot]
<img width="1920" height="1080" alt="added to cart" src="https://github.com/user-attachments/assets/a928dd91-23cf-4a9f-a669-e357b87ee810" />


## Conclusion

This documentation should provide a clear understanding of how to utilize the Postman collection for testing the ShopperStack e-commerce site.




