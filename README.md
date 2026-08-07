Student Information Management System

System Overview

The Student Information Management System is a web-based application that helps administrators manage student records, courses, and enrollments efficiently.

Problem Statement

Manual management of student records is slow and prone to errors. A web-based system provides faster, more accurate, and organized record management.

Three-Tier Architecture

Presentation Layer

- Login page
- Dashboard
- Student management pages
- Forms and reports

Responsibilities

- Display information
- Accept user input
- Send requests to the application layer

Application Layer

- PHP business logic
- Authentication
- Validation
- CRUD operations

Responsibilities

- Process user requests
- Validate data
- Communicate with the database

Data Layer

- MySQL Database

Tables

- Users
- Students
- Courses
- Enrollments

Responsibilities

- Store data
- Retrieve data
- Update and delete records

Architecture Diagram

        User
          |
          v
+----------------------+
| Presentation Layer   |
| HTML / CSS           |
+----------------------+
          |
          v
+----------------------+
| Application Layer    |
| PHP                  |
+----------------------+
          |
          v
+----------------------+
| Data Layer           |
| MySQL Database       |
+----------------------+

Data Flow

1. User enters information.
2. Presentation layer sends the request.
3. Application layer processes the request.
4. Data layer stores or retrieves data.
5. Results are returned to the user.

Proposed Database Plan

Users

- user_id
- username
- password
- role

Students

- student_id
- first_name
- last_name
- course
- year_level

Courses

- course_id
- course_name

Enrollments

- enrollment_id
- student_id
- course_id

Architectural Design Justification

The Three-Tier Client-Server Architecture separates the user interface, business logic, and database. This improves maintainability, security, scalability, and makes the application easier to develop and manage.

Conclusion

Using a Three-Tier Architecture creates a well-organized, secure, and efficient Student Information Management System suitable for managing school records.
Module 6 – Architectural Design

Student Information

Name: Resuello Nazer

Course: BSCS

Project Title

Student Information Management System

Description

This project documents the architectural design of a simple web-based Student Information Management System using a Three-Tier Client-Server Architecture.

Repository Structure

- README.md
- docs/architecture.md

Technologies Used

- HTML
- CSS
- PHP
- MySQL
- Git
- GitHub

Author

Resuello Nazer