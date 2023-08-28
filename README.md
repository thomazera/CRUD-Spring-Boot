# CRUD-Spring-Boot
CRUD - Explantion

MAIN FEATURES:

Operate database connections (Create, Read, Update and Delete)
User creation with name and email, id is automatic
Run locally

Pre requirements:

Docker (with docker-compose)
In the project folder run the following commands:

Inside the project folder, run the project with :
mvn clean package -DskipTests
docker compose build
docker compose up

Install TablePlus:
"+" -> PostgreSQL
Host: localhost
Port: 5432
User: postgres
Password: postgres
"Test" -> Click on
"Connection" -> Click on


Note that this application uses the following ports:

8080 (Application)
5432 (PostgreSQL)
Also note that as no volume was created for PostgreSQL database container, the data is restored everytime you rerun the project.

Test Scenarios Skiped

**

Technologies


Docker
Java 17
Spring Boot 3
Maven
PostgreSQL
TablePlus


Contact

Thomas Olympio

E-mail: thomaseduardoolympio@gmail.com
