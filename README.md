# Q2 – Library Management REST API using Spring Boot

A RESTful Library Management API developed using **Java, Spring Boot and Maven** as part of the KIET CS336B MSE-II assignment.

## Project Overview

This project demonstrates the development and execution of a backend REST API using Spring Boot.

The application runs on an embedded Apache Tomcat server and accepts HTTP requests through API endpoints. Postman can be used to send requests and test the application's functionality.

## Features

- REST API development using Spring Boot.
- HTTP request handling.
- Backend application execution using embedded Tomcat.
- API testing using Postman.
- JSON-based request and response handling.

*Refer to the implemented controller classes for the exact supported library operations.*

## Technologies Used

- Java
- Spring Boot 3.3.5
- Spring Web
- Maven
- Apache Tomcat
- Postman
- IntelliJ IDEA

## Project Information

| Property | Details |
|---|---|
| Project Name | Q2-SpringBoot-LibraryAPI |
| Main Class | LibraryApplication |
| Framework | Spring Boot |
| Server | Embedded Apache Tomcat |
| Default Port | 8080 |
| API Testing | Postman |

## Getting Started

### Prerequisites

- Java JDK
- IntelliJ IDEA
- Maven
- Postman

### Installation

1. Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Open the project in IntelliJ IDEA.
3. Wait for Maven dependencies to download.
4. Open `LibraryApplication.java`.
5. Run the main application.

### Running the Application

Once the application starts successfully, the embedded Tomcat server runs on:

```text
http://localhost:8080
```

## Testing with Postman

1. Open Postman.
2. Create a new HTTP request.
3. Set the appropriate HTTP method (GET, POST, PUT or DELETE).
4. Enter the endpoint URL defined in the project's controller classes.
5. For POST and PUT requests, select Body → raw → JSON and provide the required JSON data.
6. Click Send to view the API response.

### Base URL

```text
http://localhost:8080
```

**Note:** The exact API endpoints and JSON request structures depend on the implemented controller and model classes.

## Concepts Demonstrated

- Spring Boot application development
- REST API architecture
- HTTP methods
- Embedded Apache Tomcat server
- JSON request and response handling
- Maven dependency management
- Backend application execution
- API testing using Postman

## Author

Developed as part of the KIET CS336B MSE-II assignment.
