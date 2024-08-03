# Task Management Application

## Overview

This is a Task Management application built using Spring Boot. It allows users to create, read, update, and delete tasks. The application demonstrates basic CRUD operations and integrates with an H2 in-memory database for simplicity.

## Features

- **Create**: Add new tasks to the list.
- **Read**: View all tasks or a specific task.
- **Update**: Modify the details of existing tasks.
- **Delete**: Remove tasks from the list.

## Technologies Used

- **Spring Boot**: Framework for building the application.
- **JPA (Java Persistence API)**: Provides the interface for interacting with the database.
- **Hibernate**: ORM tool used with JPA for database operations.
- **H2 Database**: In-memory database for development and testing.
- **Maven**: Build tool used for project management.

## Setup

### Prerequisites

- Java 11 or later
- Maven

### Installation

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/YOUR_USERNAME/Task-Management.git
   
2. **Navigate to the project directory:**
   ```bash
   cd Task-Management

3. **Build the project:**
     ```bash
   mvn clean install

4. **Run the application:**
     ```bash
   mvn spring-boot:run

## Testing
You can test the API endpoints using tools like Postman or curl. Ensure the application is running locally before testing the endpoints.
