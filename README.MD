# CRUD Application

This project is a RESTful CRUD application built using Spring Boot. The application implements standard RESTful practices and follows a layered architecture.

This was developed as part of the [Building a REST API with Spring Boot](https://spring.academy/courses/building-a-rest-api-with-spring-boot) course from Spring Academy.

Family Cash Card is an app for families to manage allowances in the form of digital debit cards.

## Key Features

- **HTTP Methods**: Implemented RESTful operations using `GET`, `PUT`, `PATCH`, and `POST`.
- **Response Status Codes**: Proper handling of HTTP status codes such as `200 OK`, `201 CREATED`, and `204 NO CONTENT`.
- **Layered Architecture**:
    - **Spring Security**: Secures the API endpoints.
    - **Spring Web**: Handles HTTP communications between the API and clients.
    - **Spring Data**: Manages interaction with the relational data store.


## Development Approach

- **Test-First Development**: Ensured functionality using a test-driven development (TDD) approach.
- **Steel Thread Implementation**: Focused on driving out core functionality and de-risking integration points early in development.
- **Red, Green, Refactor**: Followed the TDD cycle to iteratively improve code quality and coverage.

## Technologies Used

- Java
- Spring Boot
- Spring Security
- Spring Web
- Spring Data JPA
- JUnit (Testing)

## Running the Test Suite

To run the test suite, execute the following command:

```bash
mvn test
```

## How to Run

1. Clone the repository.
2. Run `mvn clean install` to build the project.
3. Start the application using `mvn spring-boot:run`.
4. Access the API via `http://localhost:8080`.
