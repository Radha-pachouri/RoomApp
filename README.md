<h1 align = "center">Room Application</h1>
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.0.5-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
  <a >
    <img alt="MySQL" src="https://img.shields.io/badge/MySQL-blue.svg">
</a>
</p>

This project is a Room App  that allows users to manage rooms. It provides endpoints for CRUD operations on rooms model
<br>

## Framework Used
* Spring Boot

---
<br>

## Dependencies
The following dependencies are required to run the project:

* Spring Boot Dev Tools
* Spring Web
* Spring Data JPA
* MySQL Driver
* Lombok
* Validation

<br>

## Database Configuration
To connect to a h2 console database, update the application.properties file with the appropriate database URL, username, and password. The following properties need to be updated:
```
spring.datasource.url=jdbc:h2:mem:h2db
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=room
spring.datasource.password=room
spring.jpa.database-platform=org.hibernate.dialect.H2Dialect



spring.h2.console.enabled=true
spring.jpa.properties.hibernate.show_sql=true
spring.jpa.properties.hibernate.use_sql_comments=true
spring.jpa.properties.hibernate.format_sql=true

##http://localhost:8080/h2-console

```
<br>

## Language Used
* Java

---
<br>

## Data Model

<br>
The room data model is fined the all the rooms like ac and non ac has the following attributes:

* Room:
```
 * private String roomId;
 * private String roomNumber;
 * private String roomType;
 * private String roomAvailble;
 * private String roomPrice;
 ```

<br>

## DataBase Used
* H2 console database
```
We have used Persistent database to implement CRUD Operations.
```
---
<br>

---

# Project Summary
### The project is a basic web application built using Java and the Spring framework. this framwork used for get details of all rooms...with tha help of crud operations like create read update and delete...
<br>
