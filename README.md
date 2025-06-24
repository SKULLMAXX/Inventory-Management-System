Inventory Management System

A full-stack Inventory Management System developed with Angular for the frontend, Spring Boot for the backend, and MySQL as the database. This system allows users to efficiently manage products, suppliers, and orders, providing a seamless experience for businesses to track and maintain their inventory.

Features:

* Product Management — Add, update, delete, and view products.
* Supplier Management — Maintain a list of suppliers.
* Order Management — Track and manage orders.
* Search & Filter — Quickly locate products by name, category, or supplier.
* Database Integration — Persistent storage using MySQL.
* REST APIs — RESTful services built with Spring Boot.
* Modern Frontend — Responsive and dynamic Angular user interface.

Database Configuration:
Edit the following in src/main/resources/application.properties:

spring.datasource.url=jdbc\:mysql://localhost:3306/inventory\_db
spring.datasource.username=your\_mysql\_user
spring.datasource.password=your\_mysql\_password
spring.jpa.hibernate.ddl-auto=update

Build and run the backend:
mvn clean install
mvn spring-boot\:run

Frontend (Angular):

Navigate to the Angular directory:
cd frontend

Install dependencies:
npm install

Start the Angular app:
ng serve
