# **CommerceCore - E-Commerce RESTful API**

This repository contains the source code for **CommerceCore**, a fully-featured E-Commerce platform developed using Node.js and Express.js. The application is designed following RESTful principles and integrates various modern technologies to deliver a robust backend solution.

## **Project Overview**

**CommerceCore** is an E-Commerce platform where users can browse products, manage shopping carts, and complete purchases. The platform also includes features such as user authentication, product reviews, and order management. The backend is built to handle all business logic, database interactions, and secure payment processing.

## **Features**

- **Product Management**: Create, read, update, and delete (CRUD) operations for products, including filtering, sorting, and pagination.
- **Category and Subcategory Management**: Organize products into hierarchical categories and subcategories.
- **User Authentication and Authorization**: Secure user authentication using JWT, role-based access control (Admin, Manager, User), and password recovery.
- **Shopping Cart and Coupons**: Manage shopping cart items, apply discount coupons, and handle cart operations.
- **Order Processing**: Support for both cash and online payments, with order management and payment gateway integration.
- **Review and Wishlist Management**: Allow users to review products, calculate average ratings, and manage wishlists.
- **Image Upload and Processing**: Handle single and multiple image uploads with server-side processing for performance optimization.
- **Security Enhancements**: Implement data validation, error handling, and protection against common web vulnerabilities.

## **Technologies Used**

- **Node.js**: JavaScript runtime used for building the server-side application.
- **Express.js**: Web framework for Node.js, used to create the RESTful API.
- **MongoDB**: NoSQL database used for storing application data.
- **Mongoose**: ODM library for MongoDB, used for data modeling.
- **JWT (JSON Web Token)**: Used for secure user authentication.
- **Multer**: Middleware for handling file uploads.
- **Stripe API**: Payment processing integration for handling online transactions.

## **Installation**

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/CommerceCore-ecommerce.git
    ```

2. **Install the dependencies:**

    ```bash
    cd CommerceCore-ecommerce
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and include the following configurations:

    ```bash
    NODE_ENV=development
    PORT=5000
    MONGO_URI=your_mongoDB_connection_string
    JWT_SECRET=your_jwt_secret
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. **Run the application:**

    ```bash
    npm run dev
    ```

5. **Access the application:**

    Visit `http://localhost:5000` in your web browser.

## **Project Structure**

- `models/`: Contains all Mongoose models for the database.
- `routes/`: Defines the API routes for handling different operations.
- `controllers/`: Implements the business logic for each API endpoint.
- `middlewares/`: Includes custom middleware functions for authentication, error handling, etc.
- `config/`: Holds configuration files, including database connection and environment settings.

## **Deployment**

This application is configured to be deployed on platforms like Heroku, with support for environment-specific configurations and secure deployment practices.

## **Contributing**

Contributions to this project are welcome. Feel free to open issues for bug reports or feature requests, and submit pull requests with your improvements.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
