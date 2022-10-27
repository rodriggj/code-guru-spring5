# Section 2 - Building a Spring Web App

## Spring Initializr - What is it? 

### Reference
- [ ] Github repo [here](https://github.com/spring-io/initializr)

### Spring Boot Starters
> What is it: A series of Dependency packages (modules, XML POM files, etc) or otherwise known as Bill of Materials (BOM) of needed packages & dependencies to start a Spring Boot project.

- [ ] Spring Boot Starters [here](https://github.com/spring-projects/spring-boot/tree/main/spring-boot-project/spring-boot-starters)

### Web Version of Spring Initializer

> This is a web front-end to the Spring Boot starters. You can input a series of params and the result is a .zip file that can be imported into our Root Directory for our source code that will manage all the needed dependencies for the project we are about to initialize with Spring Boot. 

- [ ] Spring.io [here](https://start.spring.io/)

-------------

## Web Project - Spring Initializer Configuration

1. Go to Spring Initializer [here](https://start.spring.io/)
2. Configure the Spring Project
+ Project -> _Maven Project_
+ Language -> _Java_
+ Spring Boot -> _2.2.2_
+ Project Metadata 
    + Group -> _guru.springframework_
    + Artifact -> spring5webapp
    + Options 
        + Name -> _defaults to Artifact above_
        + Description -> _Simple Web Application_
        + Package Name -> _guru.springframework.spring5webapp_
        + Packaging -> _jar_
        + Java -> 8
+ Dependencies 
    + Web
        + Spring Web
    + SQL 
        + Spring Data JPA
        + H2 Database

Click _Generate_

> Result if successfull will be a zip file that will download to your local machine. 

-------------
