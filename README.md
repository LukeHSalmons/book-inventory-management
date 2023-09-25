# Book Store

Book Store is a web application that provides a platform for users to browse, purchase, and review books. It offers a seamless user experience to explore a wide range of books available in the store.

## Features

- **User Authentication**: Secure sign up and sign in functionality to access the platform.
- **Book Browsing**: Explore a vast collection of books by various authors and genres.
- **Purchase System**: Seamless integration for purchasing your favorite books.
- **User Reviews**: Share your thoughts and reviews on books you've read.
- **User Profile**: Manage your personal details, purchase history, and wishlist.

## Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/LukeHSalmons/book-store.git
   ```

2. **Navigate to the project directory**:
   ```
   cd book-store
   ```

3. **Install dependencies**:
   ```
   npm install
   ```

4. **Set up environment variables**:

   - Create a `.env` file in the project root directory.
   - Add the following variables to the `.env` file:
     ```
     MONGODB_URI=mongodb+srv://<username>:<your-own-password>@cluster.mongodb.net/book-store?retryWrites=true&w=majority
     ```

5. **Start the application**:
   ```
   npm start
   ```

   Open your browser and visit `http://localhost:3000` to access the application.

## Backend Integration

The Book Store frontend is designed to work with a corresponding backend API for user authentication, book management, and reviews. Ensure you have set up and configured the backend API correctly.

For more information on setting up the backend API, please refer to the Book Store backend documentation.

## Dependencies

The following dependencies are used in this project:

- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **Mongoose**: Elegant MongoDB object modeling for Node.js.
- **Passport**: Express-compatible authentication middleware for Node.js.
