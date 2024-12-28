Login and Registration System

Project Overview

This project is a simple login and registration system implemented using Java Servlets, JSP, and MySQL. It allows users to register with their details, log in using valid credentials, and provides feedback if login fails.

Features

User Registration:

Users can register by providing their name, email, and password.

Registration data is stored in the MySQL database.

User Login:

Users log in with their registered email and password.

On successful login, users are redirected to the index.jsp page.

On failure, an error message is displayed using SweetAlert.

Input Validation:

The system verifies email and password combinations before granting access.

Feedback and Alerts:

Success or failure messages are displayed using SweetAlert for an improved user experience.

Technology Stack

Backend:

Java Servlets

JDBC for database connectivity

Frontend:

HTML/CSS for structure and styling

JSP for dynamic content rendering

SweetAlert for interactive alerts

Database:

MySQL


Run the Application:

Deploy the project on your server.

Access the application via http://localhost:8080/your_project_name/.

Files and Structure

Frontend:

login.jsp: Login page for user authentication.

registration.jsp: Registration page for new users.

index.jsp: Dashboard after successful login.

Backend:

Login.java: Handles user login functionality.

RegistrationServlet.java: Handles user registration functionality.

Database:

userdb: MySQL database storing user details.




Notes

Ensure the database is running before starting the server.

Update database credentials in the servlet files as per your local setup.

Test the application thoroughly with various inputs.

Future Enhancements

Add password encryption for better security.

Implement "Forgot Password" functionality.

Add input validation for stronger protection against SQL injection.


