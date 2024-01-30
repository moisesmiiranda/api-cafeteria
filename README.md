# Cafeteria API

Welcome to the Cafeteria API project!

## Overview

The Cafeteria API is a Java-based web service built using Spring Boot. It provides endpoints to manage customers, products, queue management, receive customer feedback, and store ratings for services and products.

## Features

- **Customer Management**: Allows the creation, retrieval, updating, and deletion of customer records.
- **Product Management**: Provides functionalities to manage products available in the cafeteria.
- **Queue Management**: Manages the queue/waitlist for customers.
- **Feedback System**: Enables customers to submit feedback about their experience.
- **Rating System**: Stores ratings for both service and products offered by the cafeteria.

## Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL

## Getting Started

1. **Clone the repository**:

   ```bash
   git clone https://github.com/moisesmiiranda/api-cafeteria.git
2. **Set up PostgreSQL**:

- Ensure you have PostgreSQL installed locally or use Docker to run it as a container.
- Update the application.properties file with your PostgreSQL connection details.

3. **Build and Run the Application:**
   - Navigate to the project directory and run the following command:
     ```bash
     ./mvnw spring-boot:run
4. **Accessing the API:**
   -Once the application is running, you can access the API endpoints using a tool like Postman or by making HTTP requests directly.
5. **Testing:**
 -Use automated tests provided in the project to ensure the application functions as expected.
