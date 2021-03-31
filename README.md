# Angular 11 + Spring Boot + MongoDB: Build a CRUD example

Run Spring Boot Server
-----------------------

Run Spring Boot application with Maven command: mvn spring-boot:run.

Run the Angular 11 App

You can run this App with command: ng serve --port 8081.
If the process is successful, open Browser with Url: http://localhost:8081/ and check it.

Project Explanation
-------------------

In this tutorial, we will learn how to build a full stack Angular 11 + Spring Boot + MongoDB example with a CRUD App. The back-end server uses Spring Boot with Spring Web MVC for REST Controller and Spring Data JPA for interacting with MongoDB database. Front-end side is made with Angular 11, HTTPClient & Router.

We will build a full-stack Tutorial Application in that:

- Each Tutorial has id, title, description, published status.
- We can create, retrieve, update, delete Tutorials.
- We can also find Tutorials by title.
- The images below shows screenshots of our System.

Add an object:

![angular-11-spring-boot-mongodb-example-crud-create-tutorial](angular-11-spring-boot-mongodb-example-crud-create-tutorial.png)

Retrieve all objects:

![angular-11-spring-boot-mongodb-example-crud-retrieve-all-tutorial](angular-11-spring-boot-mongodb-example-crud-retrieve-all-tutorial.png)

Click on **Edit** button to go to a Tutorial page:

![angular-11-spring-boot-mongodb-example-crud-retrieve-one-tutorial](angular-11-spring-boot-mongodb-example-crud-retrieve-one-tutorial.png)

On this Page, you can:

- change status to *Published* using **Publish** button
- delete the Tutorial using **Delete** button
- update the Tutorial details with **Update** button

![angular-11-spring-boot-mongodb-example-crud-update-tutorial](angular-11-spring-boot-mongodb-example-crud-update-tutorial.png)

Search Tutorials by title:

![angular-11-spring-boot-mongodb-example-crud-search-tutorial](angular-11-spring-boot-mongodb-example-crud-search-tutorial.png)

## Angular 11, Spring Boot & MongoDB Architecture
This is the application architecture we will build:

![angular-11-spring-boot-mongodb-example-crud-architecture](angular-11-spring-boot-mongodb-example-crud-architecture.png)

- Spring Boot exports REST Apis using Spring Web MVC & interacts with MongoDB Database using Spring Data MongoDB.
- Angular 11 Client sends HTTP Requests and retrieve HTTP Responses using axios, shows data on the components. We also use Angular Router for navigating to pages.

