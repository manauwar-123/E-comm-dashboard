# E-Commerce Backend

This project is a full-stack e-commerce application with a Node.js backend and a React frontend. It provides user authentication, product management, and search functionality.

## Table of Contents

- [Features](#features)
- [Backend](#backend)
- [Frontend](#frontend)
- [Setup](#setup)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and login with JWT authentication
- Product management (Add, Update, Delete, List)
- Product search functionality
- Protected routes for authenticated users

## Backend

The backend is built with Express.js and uses MongoDB for data storage. It provides RESTful API endpoints for user authentication and product management.

Key files:
- `index.js`: Main server file with API routes
- `db/config.js`: Database configuration
- `db/User.js`: User model
- `db/Product.js`: Product model

## Frontend

The frontend is built with React and uses React Router for navigation.

Key files:
- `App.js`: Main component with routing configuration
- `components/`: Directory containing all React components
- `components/Nav.js`: Navigation component
- `components/PrivateComponent.js`: HOC for protected routes
- `components/SignUp.js`: User registration component
- `components/Login.js`: User login component
- `components/AddProduct.js`: Add product component
- `components/ProductList.js`: List products component
- `components/UpdateProduct.js`: Update product component

## Setup

1. Clone the repository
2. Install dependencies for both backend and frontend:


