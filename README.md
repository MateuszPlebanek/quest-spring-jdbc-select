# Spring JDBC - School Challenge

Project completed as part of a Spring Boot and JDBC challenge.

## Objective

The application allows users to display and search for magic schools stored in a MySQL database.

## Technologies Used

- Java
- Spring Boot
- JDBC
- MySQL
- Thymeleaf
- Maven

## Database

Database used:

spring_jdbc_quest

## Main tables

wizard
school

## Features implemented
- Display all schools
- Search for a school by ID
- Search for schools by country
- Connect to MySQL using JDBC
- Use PreparedStatement for SQL queries
- Map SQL results to School objetcs

## Project Structure
JDBC database access is handled in:

SchoolController.java
The JDBC code is kept in the repository layer rather than in the controller.

## Running the project
Run:

WildAndWizardApplication.java

# The open:
http://localhost:8080


