# Student Registration System

## About the Project

This is a Spring Boot CRUD web application developed for COSC 32133 / BECS 32263 Full-Stack Software Development — Lab Sheet 04 at the University of Kelaniya.

The application allows users to register students, view student records, edit student details, and delete records. It uses Spring Boot, Thymeleaf, Spring Data JPA, and an H2 database.

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Thymeleaf
- Maven
- Git and GitHub

## How to Run

### Prerequisites

- JDK 21 (or the Java version configured in `pom.xml`)
- Git
- Internet connection for the initial dependency downloads

### Steps

1. Clone the repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Open the project folder in VS Code or another Java IDE.

3. Open a terminal in the project directory.

4. Run the application on Windows:

   ```powershell
   .\mvnw.cmd spring-boot:run
   ```

5. Open the application in your browser:

   http://localhost:8080/students

## H2 Database Console

Open:

http://localhost:8080/h2-console

Use the following settings:

- JDBC URL: `jdbc:h2:mem:studentdb`
- Username: `sa`
- Password: Leave empty

The H2 database is configured as an in-memory database. Records are lost when the application stops.

## Features

- Register students
- View all registered students
- Edit student details
- Delete student records
- Validate student information
- Prevent duplicate email addresses

