# Manager Lotniczy - Spring Boot Application
The project was created in Polish language without use any ORM to fulfill the requirements of the "Bazy Danych 1" course at the AGH University.  
Check out repository with database project: <a href="https://github.com/k-czerwinski/flight-manager-database">flight-manager-database</a>
## Overview

This Spring Boot application, named "Manager Lotniczy," serves as a comprehensive management system for handling flights-related operations.
The project focuses on providing a user-friendly interface and robust functionalities for managing flights, employees, and other relevant aspects of airline operations.

## Functionalities

### 1. Flight Management

Users, both administrators and regular clients, can:

- List flights based on departure and arrival airports, price, and dates.
- Purchase tickets for specific flights.
- View flight details, including routes, schedules, and aircraft information.

### 2. Shop Management

Clients have the ability to:

- List available shops at airports.
- Filter shops based on airports and shop categories.
- Explore details about each shop.

### 3. Admin Features

Administrators, after logging in, can perform the following operations:

- View, sort, paginate, and add new flights.
- View, sort, paginate, and add new airlines.
- Generate and view reports on airport employees, airline details, and airport shop categories.
- View, sort, paginate, and add new flights.
- View, sort, paginate, and add new employees' functions.
- View, sort, paginate, filter, and add new shops.
- View, sort, paginate, and add new aircraft.

### 4. Security

The application uses Spring Boot Security for user authentication and authorization.

## Technologies Used

The application utilizes the following technologies:

- **Spring Boot**: The core framework for building the application.
- **Spring Boot JDBC**: Provides JDBC support for database connectivity.
- **Spring Boot Freemarker**: Integrates Freemarker as the template engine for rendering views.
- **Spring Boot Web**: Enables the development of web applications.
- **Spring Boot Security**: Incorporates security features for user authentication and authorization.
- **PostgreSQL**: The chosen relational database management system.
- **WebJars (Bootstrap, jQuery)**: Manages web libraries like Bootstrap and jQuery.
- **Java 21**: The specified Java version for development.

## Building and Running the Application

To build and run the application:

1. Clone <a href="https://github.com/k-czerwinski/flight-manager-database">database repository</a> and execute SQL scripts to create the database and populate it with data.
2. Ensure you have Java 21 installed on your machine.
3. Clone the project from the repository.
4. Open the project in your preferred IDE.
5. Build the project using Maven.
6. Run the application.

Feel free to explore the various functionalities by accessing the provided URLs or endpoints based on the defined features.
