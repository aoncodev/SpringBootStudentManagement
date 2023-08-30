# Spring Boot Student Management

This is a simple Spring Boot application that demonstrates basic CRUD (Create, Read, Update, Delete) operations for managing student records.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Description

This project is a part of my journey in learning Spring Boot. It includes a RESTful API for managing student records. The application uses Spring Boot Data JPA for database interactions and provides endpoints for adding, updating, deleting, and retrieving student information.

## Features

- Add a new student with name, date of birth, and email.
- Delete a student by their ID.
- Update a student's name and email.
- Retrieve a list of all students.

## Technologies

- Java 19
- Spring Boot 3.1.3
- Spring Boot Data JPA
- PostgreSQL (Database)
- Maven (Build Tool)

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/aoncodev/SpringBootStudentManagement.git
   cd SpringBootStudentManagement

2. **Database Setup:**

- Install PostgreSQL and create a database named `student_management`.
- Update the database configuration in `src/main/resources/application.properties` to match your database settings.
3. **Build and Run:**
 `mvn spring-boot:run`

## Usage

- Access the API at: http://localhost:8080/api/v1/student.html
- Use the provided endpoints to interact with student records.

## Contributing
Contributions are welcome! If you find any issues or want to add enhancements, feel free to submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Create a pull request.

## License
This project is licensed under the MIT License