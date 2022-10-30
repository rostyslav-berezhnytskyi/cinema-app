![cinema-1269996](https://user-images.githubusercontent.com/108344763/198120034-dabf350b-5192-4f98-b398-7ed2e8c354e1.jpg)
## Description
This application is simple cinema shop management service.
Users: You can register a new account as USER, login, work or logout later.
Cinema: There are different cinema-halls, movies and movie-sessions with different time and parameters.
Orders: Users can place orders through the shopping cart, pre-generated tickets with movie-sessions.

## Project structure
**The project has an N-Tier Architecture**
- Controller - allows the user to work with this application.
- Service - responsible for processing the data received from the DAO level.
- DAO - responsible for communicating with the database.
- MySQL database.

## Features
- Registration
- Authentication
- Login / Logout
- Setting roles for users (USER by default)
- Creating and deleting movies and movie sessions (can be performed by ADMIN)
- Buying tickets for movie session (can be performed by USER)

## Technologies
- Java 11
- Maven
- MySQL
- Tomcat
- Hibernate
- Spring Web/Security

## Quickstart
1. Fork this repository
2. Copy link of project
3. Create new project from Version Control
4. Edit resources/db.properties - set the necessary parameters
``` java
    db.driver=YOUR_DRIVER
    db.url=YOUR_URL
    db.user=YOUR_USERNAME
    db.password=YOUR_PASSWORD
```
5. Create the necessary name of DB
6. Install [Tomcat](https://tomcat.apache.org/download-90.cgi)
7. Add Tomcat server to configuration and Fix it.
8. Run project

## Example of parameters for db.properties
``` java
    db.driver=com.mysql.cj.jdbc.Driver
    db.url=jdbc:mysql://localhost:3306/NameOfDataBase?useUnicode=true&serverTimezone=UTC
    db.user=root
    db.password=123456
```
