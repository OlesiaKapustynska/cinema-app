## Cinema app 
This project is the implementation of the main functions of interaction between the cinema and the user.
![pic](https://www.pngkit.com/png/full/10-100286_cinema-png-image-film.png)
###Technologies used:
- Spring - Core / MVC / Web / Security
- Hibernate
- Database - MySQL
- Packaging - Apache Maven 
- Tomcat
***
###Setup:
1. Clone the project into your local directory and then open it in an IDE.
1. Fill in the fields (db.url, db.user and db.password) in the /src/main/resources/db.properties. In this project using MySQL DB, if you use another database you need to change field "db.driver" and dependencies in web.xml.
1. Configuration Local Tomcat: deployment - war_exploded, context address - "/"
1. Run a project
1. Admin and User will be added to your database when the program starts. You can log in as: Admin: (name: "admin123@i.ua", password:"amin123"), or User: (name: "user123@i.ua", password:"user123")
***
####A person without a role can:
- register
####An admin can:
- create a new movie session, and also delete and update it
- add new cinema hall, movie
- find user by email
####A user can:
- add the ticket for the movie to the shopping cart
- complete the order
- view all tickets in the shopping cart and history of all the orders
####Also, a user and an admin can:
- view all cinema halls, movies, available movie sessions
