# Book Inventory Management

Book Inventory Management is a comprehensive web application that offers a platform for users to manage their book inventory seamlessly. It provides functionalities to add, update, delete, and view books in the inventory.

## Features

- **User Authentication**: Secure sign up and sign in functionality to access the platform.
- **Inventory Management**: Add, update, delete, and view books in the inventory.
- **Search Functionality**: Quickly find books based on title, author, or genre.
- **User Profile**: Manage your personal details and view your activity history.

## Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/LukeHSalmons/book-inventory-management.git
   ```

2. **Navigate to the frontend directory and install dependencies**:
   ```
   cd book-inventory-management/frontend
   npm install
   ```

3. **Navigate to the backend directory and install dependencies**:
   ```
   cd ../backend
   npm install
   ```

4. **Set up environment variables for the backend**:

   - Create a `.env` file in the backend directory.
   - Add the following variable to the `.env` file:
     ```
     MONGODB_URI=mongodb+srv://<username>:<your-own-password>@cluster.mongodb.net/book-inventory?retryWrites=true&w=majority
     ```

5. **Start the frontend application**:
   ```
   cd ../frontend
   npm run dev
   ```

6. **Start the backend application**:
   ```
   cd ../backend
   npm run dev
   ```

   Once both applications are running, open your browser and visit `http://localhost:3000` (or the appropriate port) to access the application.

## Backend Integration

The Book Inventory Management frontend is designed to work seamlessly with its corresponding backend API for user authentication and inventory management. Ensure you have set up and configured the backend API correctly.

For more information on setting up the backend API, please refer to the Book Inventory Management backend documentation.

## Dependencies

The following dependencies are used in this project:

- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **Mongoose**: Elegant MongoDB object modeling for Node.js.
- **Passport**: Express-compatible authentication middleware for Node.js.
- **React**: JavaScript library for building user interfaces.
