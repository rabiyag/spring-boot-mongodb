# Spring Boot MongoDB

This project demonstrates a **Spring Boot** application that connects to a **MongoDB** database to perform CRUD operations. It uses **Spring Data MongoDB** to interact with MongoDB collections, showcasing simple and effective NoSQL data management with Spring Boot.


## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Running the Application](#running-the-application)
- [Usage](#usage)

## Features
- Integration with **MongoDB** using **Spring Data MongoDB**
- REST API endpoints for CRUD operations
- Simple configuration for MongoDB connection

## Technologies Used
- **Spring Boot** (Backend framework)
- **Spring Data MongoDB** (MongoDB support)
- **MongoDB** (NoSQL database)
- **Maven** (Dependency management)


## Project Structure
```
src/main/java
    ├── controller      # Controller handling API requests
    ├── model           # Data models representing MongoDB documents
    ├── repository      # MongoDB repository interfaces for data access
    ├── service         # Service layer to handle business logic 
src/main/resources
    └── application.properties # Database connection and application configuration

```

## Prerequisites
- **JDK 8** or higher
- **Maven** for dependency management
- **PostgreSQL** database

## Setup
1. **Clone the repository**:
   ```bash
    git clone https://github.com/rabiyag/spring-boot-mongodb.git
   cd spring-boot-mongodb
   ```
   
2. **Configure MongoDB**:
   - Open application.properties and configure your MongoDB connection details:
    ```sql
    spring.data.mongodb.host=localhost
    spring.data.mongodb.port=27017
    spring.data.mongodb.database=your_database
    ```
    
3. **Build the project with Maven**:
   ```bash
   mvn clean install
   ```

## Running the Application
1. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

2. **Access the application**:
   - The application will be available at http://localhost:8080:
  

## Usage
The project provides RESTful endpoints to interact with MongoDB for CRUD operations. You can use tools like Postman to test the API endpoints.
