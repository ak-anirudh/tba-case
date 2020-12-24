# YARD MODULE - TBA

## Description

This project contains of two parts -
- [Cranes]() - API to create and manipulate the cranes
- [UI]() - cmd line interface to execute the tasks

For building and running the application you need:

- [JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven 3](https://maven.apache.org)

## Running the application locally

There are several ways to run the application on your local machine. 
- One way is to execute the `main` method in the `org.tbaCase.Cranes.Application` class and `org.tbaCase.UI.Application` from your IDE.

- Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn clean install
mvn spring-boot:run
```

## 