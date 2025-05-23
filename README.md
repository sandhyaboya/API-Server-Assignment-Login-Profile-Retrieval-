# API-Server-Assignment-Login-Profile-Retrieval-
Project Description:
This is a simple RESTful API server developed as part of an assignment to demonstrate user login functionality and profile retrieval using a relational database.

The project consists of two main endpoints:

POST /api/users/login: Authenticates a user based on username and password.

GET /api/users/{username}: Retrieves the user’s profile details (first name, last name, age) for a given username.

The user records are directly inserted into the database (no signup/registration feature is included, as per assignment instructions). Authentication is performed using plain-text comparison for simplicity.

Technologies Used:
Backend Framework: [Spring Boot]

Database: [MySQL]

Language: [Java]

Build Tools: [Maven]

Project Structure (Sample):

/api-server-assignment
├── src/
│   ├── controllers/
│   ├── models/
│   ├── services/
│   ├── Application.java
├── resources/
│   ├── application.properties
├── database/
│   ├── schema.sql
│   ├── data.sql
├── README.md
 Features:
Login validation using a /login endpoint

User profile retrieval by username

Basic error handling for invalid login or missing users

Sample user records and SQL scripts for quick setup

