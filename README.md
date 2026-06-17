# Dynamic User Authentication System

This is a demo learning project developed using PHP, MySQL, HTML, and CSS to understand the fundamentals of dynamic web development and user authentication. The application allows users to register, log in securely, access a protected dashboard through session management, and log out safely. User data is stored in a MySQL database, while PHP handles backend logic, authentication, validation, and session control. The project demonstrates database connectivity, form handling, error handling, and frontend-backend integration, making it a practical example for beginners learning full-stack web development.

## Project Structure and File Description

### 📄 index.php

The main login page of the application. It provides a user interface where registered users can enter their username and password to access the system.

### 📄 register.html

Contains the registration form used by new users to create an account.

### 📄 register.php

Processes registration requests, validates user input, checks for duplicate usernames, and stores user credentials in the MySQL database.

### 📄 login.php

Handles user authentication by verifying login credentials against the database. Upon successful authentication, it creates a session and redirects the user to the dashboard.

### 📄 dashboard.php

A protected page that can only be accessed by authenticated users. It displays a welcome message and provides access to application features after login.

### 📄 logout.php

Destroys the active session and securely logs the user out of the system before redirecting them back to the login page.

### 📄 db.php

Responsible for establishing a connection between the PHP application and the MySQL database. All database operations use this connection file.

### 🎨 style.css

The primary stylesheet of the project. It contains common styling rules, layouts, typography settings, colors, buttons, forms, navigation bars, and responsive design elements used throughout the application.

### 🎨 login.css

Provides dedicated styling for the login page, including modern layouts, form design, animations, glassmorphism effects, and interactive user interface components.

### 🎨 dashboard.css

Provides styling for the dashboard page, including navigation components, content layout, welcome section, cards, and logout button design.

---

## Technologies Used

### Frontend

* HTML5
* CSS3

### Backend

* PHP

### Database

* MySQL

### Development Environment

* XAMPP
* Visual Studio Code

---

## Project Workflow

1. New users register through the registration form.
2. Registration data is validated and stored in the MySQL database.
3. Registered users log in using their credentials.
4. The system authenticates the user against stored database records.
5. Upon successful authentication, a PHP session is created.
6. The user is redirected to the dashboard page.
7. Protected pages verify the active session before granting access.
8. The logout feature destroys the session and returns the user to the login page.

This project was developed as a demo learning project to gain practical experience with PHP, MySQL, HTML, CSS, authentication systems, session management, form handling, database integration, and dynamic web application development.
