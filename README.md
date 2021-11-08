## Simple User Management with Spring Boot and Thymeleaf

_This project is derived from Baeldung, see https://github.com/eugenp/tutorials/tree/master/spring-boot-modules/spring-boot-crud_

### Tech Stack

* Spring Boot (start with https://start.spring.io/)
* Apache Maven
* Spring Data JPA (H2 in-memory database)
* Spring MVC ([Thymeleaf](https://www.thymeleaf.org/) as template engine)

### Persistence

This demo uses a H2 in-memory database. The H2-configuration is in `application.properties`. Spring Data JPA is used for initial Schema creation.  

### Start

* Start with `mvn spring-boot:run` without IDE
* Start `main` in `Application` class with IDE
