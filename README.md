# Bike Championship
Bike Championship is open-source project developed by group of students
in SoftServe IT Academy. We are aiming to create a service that allows
you to manage bicycle competitions in a simple way.

#### Internals
In this project we are using following technologies, tools and frameworks:
Java, Spring Boot, Maven, React, Ant Design, Axios, JSON Web Token, H2, MySQL, Lombok

## How to run an app
* build and run backend module
  - verify that [Java](https://www.java.com/download/) is installed
  - start your MySQL instance and make corresponding changes in application.yml
  - proceed to _backend/_ folder and run `mvnw install` to build and install the modules
  - run `mvnw spring-boot:run -f ./server/` to launch server module
* launch frontend module using following steps:
  - verify that [Node.js](https://nodejs.org/) is installed
  - open terminal and proceed to _frontend/_ folder
  - run `npm install` to download dependencies
  - run `npm start` command to launch frontend module
