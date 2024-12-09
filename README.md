# banquemisr.challenge05
# Task Management System

## Prerequisites

* PostgreSQL

    ```sql
    create role task-management with login password 'task-management';
    create database task-management-system with owner task-management;
    ```

* JDK 11 

## IDE Configuration

* Make sure that in IntelliJ Preferences, Maven Runner is delegating the build actions to Maven.

## Task Management Project 

   * Data: Created a data.sql file containing project data.

   * Technologies: Utilized Lombok, MapStruct, Spring Security, PostgreSQL, Spring Web, Spring Data JPA, Spring Boot Starter Mail.

   * Unit Testing: Implemented unit tests for the task service.

   * Job Scheduling: Developed a scheduled job to send email notifications using demomailtrap.com for task deadlines.
