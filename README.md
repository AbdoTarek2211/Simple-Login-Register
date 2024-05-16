# Express.js Login and Registration with PostgreSQL

This is a basic web application built with Express.js that provides user registration, login, and logout functionalities using PostgreSQL as the database. It utilizes bcrypt for password hashing, express-session for session management, express-flash for flashing error/success messages, and passport.js for authentication.
Prerequisites

Before running the application, ensure you have the following installed:

    Node.js
    PostgreSQL

Installation

    Clone this repository to your local machine:

    bash

git clone <repository-url>

Navigate to the project directory:

bash

cd express-login-registration-postgresql

Install dependencies:

bash

npm install

Set up the PostgreSQL database:

    Create a PostgreSQL database.
    Update ./dbConfig.js with your PostgreSQL database configuration.

Run the application:

bash

    npm start

Usage

Once the application is running, you can access it through a web browser at http://localhost:4000.

    Register: Navigate to /users/register to create a new account.
    Login: Navigate to /users/login to log in to an existing account.
    Dashboard: After logging in successfully, you'll be redirected to /users/dashboard.
    Logout: You can log out by navigating to /users/logout.

Features

    User registration with input validation.
    Password hashing using bcrypt for security.
    Login authentication with Passport.js.
    Session management with express-session.
    Flash messages for displaying success/error messages.
    Access control to routes based on authentication status.

Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or create a pull request.
