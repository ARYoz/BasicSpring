# BasicSpring project
## Introduction
This project is a comprehensive web application built to manage student data efficiently. It features a robust backend architecture and integrates various technologies to handle data operations, user authentication, and asynchronous processes.
## Technologies Used
- **Spring Boot:** The application is developed using Spring Boot, a powerful framework for building Java-based applications. It simplifies the development process with its convention-over-configuration approach and extensive support for various integrations.

- **JPA (Java Persistence API):** Utilized for ORM (Object-Relational Mapping) to manage database interactions seamlessly. It helps in mapping Java objects to database tables and vice versa.

- **PostgreSQL:** Chosen as the relational database management system for storing and retrieving student data. PostgreSQL offers strong support for advanced data types and performance optimization.

- **AWS S3:** Used for storing and retrieving student profile pictures. AWS S3 provides scalable object storage with high durability and availability.

- **JWT (JSON Web Tokens):** Implemented for secure authentication and authorization. JWT ensures that users are authenticated before accessing protected resources.

- **Swagger:** Integrated for API documentation and testing. Swagger provides an interactive UI for exploring and testing the RESTful APIs.

- **Spring Actuator:** Included to monitor and manage application health and metrics. Actuator provides various endpoints to access application and system information.

- **Docker:** Employed for containerizing the application, ensuring consistency across different environments. Docker simplifies deployment and scaling by using lightweight containers.

- **Newman:** Used for running Postman collections in a continuous integration environment. Newman facilitates automated API testing and reporting.

- **Jenkins:** Configured for continuous integration and deployment. Jenkins automates the build, test, and deployment processes, ensuring that code changes are seamlessly integrated and deployed.

- **OpenShift:** Leveraged for orchestrating containerized applications in a Kubernetes environment. OpenShift provides a platform for managing and scaling containerized applications.

## Key Features and Updates
- **Student Data Management:** Allows for CRUD operations on student data, including uploading and retrieving student profile images.

- **Search Functionality:** Implements advanced search capabilities with filters for student attributes such as name, birth date, SAT scores, and average course scores.

- **Asynchronous SMS Integration:** Provides functionality to send SMS messages to students. This feature is integrated with an external SMS service for sending notifications.

- **Exception Handling:** Replaced generic RuntimeException with a custom HandsonException for more precise error handling and improved user experience.

- **Microservices:** Deployed microservices architecture to handle SMS notifications independently, promoting scalability and maintainability.

- **Testing and Coverage:** Included comprehensive unit tests and used Docker for testing and deployment. Ensured high test coverage and integrated testing reports into the CI/CD pipeline.

## Conclusions

This project successfully demonstrates the integration of various modern technologies to build a scalable and efficient web application for managing student data. The use of Spring Boot, JPA, and PostgreSQL ensures robust data management and performance, while JWT and Swagger enhance security and API usability. Docker and Jenkins streamline the development, testing, and deployment processes, ensuring a consistent and reliable application lifecycle.
