# LuxeLoom-E-commerce-Platform

Introduction : -

This is a full-fledged E-Commerce Application built to enable users to browse products, place orders, and make payments using Razorpay. The application provides an intuitive user interface for customers to manage their orders, and an admin panel for managing products, orders, and customers. It features robust backend support with Spring Boot and secure authentication mechanisms using JWT tokens and Spring Security.

Explanation : -

The project is structured as a full-stack application with a React.js frontend and a Spring Boot backend. Users can interact with the application to browse products, add them to their cart, and proceed to checkout, where payments are handled securely by Razorpay. Admins have the ability to manage products, confirm orders, and monitor customer activities through a dashboard. All data is stored in a MySQL database, and the entire application follows a RESTful architecture.

Technology and Tech Stack Used : -

Frontend : -

React.js: For building interactive and dynamic UI components.
Redux: For state management.
Axios: For handling API requests.
Material-UI: For styling and UI components.

Backend : -

Spring Boot: For building RESTful APIs.
Spring Security: For authentication and authorization.
JWT: For secure token-based authentication.
MySQL: For data persistence and management.
Razorpay: For payment processing.

Other Tools : -

Postman: For API testing.

Features and Functionality : -

Customer Features : -

Product Browsing: Users can browse through available products and view details.
Cart Management: Add products to the cart and proceed to checkout.
Order Placement: Users can place orders and make payments using Razorpay.
Order Tracking: View the status of orders, including confirmed, shipped, and delivered.
User Authentication: Secure login and signup with JWT-based authentication.

Admin Features : -

Product Management: Admins can add, update, and delete products.
Order Management: Admins can confirm, ship, cancel, and delete orders.
Customer Management: Admins have access to customer details and can manage user accounts.

Security : -

JWT Authentication: Secure token-based authentication for API requests.
Role-Based Access Control: Admins and customers have different access levels.

Payments  : -

Razorpay Integration: Seamless integration with Razorpay for payment processing.
