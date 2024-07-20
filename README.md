# MERN Project E-Commerce

A full-stack e-commerce application built with the MERN stack (MongoDB, Express, React, Node.js).

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Demo
[Insert a link to your live demo here]

## Features
- User authentication (register, login, logout)
- Product listing and details
- Shopping cart management
- Order management
- Admin dashboard for managing products, users, and orders
- Responsive design

## Installation

### Prerequisites
- Node.js and npm installed
- MongoDB installed and running

### Backend Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/mernProjectEcommerce.git
    cd mernProjectEcommerce
    ```

2. Install backend dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    MONGO_URI=mongodb://localhost:27017/mernproject
    JWT_SECRET=your_jwt_secret
    ```

4. Start the backend server:
    ```sh
    npm run server
    ```

### Frontend Setup
1. Navigate to the `client` directory:
    ```sh
    cd client
    ```

2. Install frontend dependencies:
    ```sh
    npm install
    ```

3. Start the frontend development server:
    ```sh
    npm start
    ```

### Running Both Servers Concurrently
From the root directory, you can run both servers concurrently:
```sh
npm run dev
