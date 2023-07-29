# CRUD using Java 20, Spring Boot, and PostgreSQL

This repository contains a simple CRUD application developed in Java 20, using the Spring Boot framework and PostgreSQL database. The CRUD allows performing basic operations of creating, reading, updating, and deleting products.

## Requirements

Make sure you have the following tools installed in your development environment:

- Java 20
- Spring Boot
- PostgreSQL

## Database Configuration

Before running the application, you need to configure the Postgres database. Follow the steps below:

1. Create a database in PostgreSQL.
2. Open the `application.properties` file located in `src/main/resources`.
3. Modify the properties `spring.datasource.url`, `spring.datasource.username`, and `spring.datasource.password` according to your database settings.

## Running the Application

To run the application, follow the steps below:

1. Clone this repository to your development environment.
2. Navigate to the project's root directory.
3. Run the following command to compile and execute the application:

```shell
./mvnw spring-boot:run
```

1. The application will be available at http://localhost:8080.
## Endpoints
The API has the following endpoints:

- GET /products: Returns all registered products.
- GET /products/{id}: Returns the details of a specific product based on the provided ID.
- POST /products: Registers a new product based on the data provided in the request body.
- PUT /products/{id}: Updates an existing product based on the provided ID and the data provided in the request body.
- DELETE /products/{id}: Deletes a product based on the provided ID.

## 👨🏽‍💻 Author:

<img src="https://avatars.githubusercontent.com/u/85323953?v=4" width="100px;" alt="foto do desenvolvedor"/>

- [@CelioAmaral](https://github.com/CelioAmaral)

<sup>Systems Analyst</sup>
</br>
<div>
  <a href="https://www.linkedin.com/in/celioamaral20" target="_blank"><img align="center" alt="Celio-Link" height="30" width="90" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=flat&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>
