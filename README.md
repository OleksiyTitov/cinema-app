# Cinema-app
This is a simple web application that supports authentication, authorization and CRUD operations.

# Technologies:
- Java
- Apache Tomcat - version 9.0.50
- Apache Maven
- MySQL
- Hibernate
- Spring MVC
- Spring Core
- Spring Security

# 3-layer architecture:
- DAO - Data access layer
- Service - Application layer
- Controllers - Presentation layer

# Endpoints:
- /register - (POST) registering a new user
- /cinema-halls - (POST) add a new cinema hall
- /cinema-halls - (GET) get all cinema halls list
- /movies - (POST) add a new movie
- /movies - (GET) get all films list
- /movie-sessions - (POST) add a new movie session
- /movie-sessions/available?movieId=<movieId>&date=<date> - (GET) get all available movie sessions
- /movie-sessions/{id} - (PUT) update a movie session
- /movie-sessions/{id} - (DELETE) delete a movie session
- /orders/complete - (POST) completing the order by the user
- /orders - (GET) get users order history
- /shopping-carts/movie-sessions - (PUT) add a session to a shopping cart
- /shopping-carts/by-user - (GET) get users shopping cart
- /users/by-email - (GET) find user by email

# How to start the program :
1) Install MySQL
2) Install Apache Tomcat version 9.0.*
3) Configure Apache Tomcat for your IDE
4) Configure db.properties with your JDBC_DRIVER, URL, USERNAME, PASSWORD
5) Start the application
6) Login using default username and password(login: admin@i.ua, password: admin123)
