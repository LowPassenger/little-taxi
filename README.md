![Taxi-02](images/Taxi-02.jpg)

#   <u>&euro;   Little taxi - Your taxi service! &euro;</u>  

*Welcome to my first application)

Image that you are a lucky owner of little taxi service, so I have created this 
web application specially for you! You have a few vehicles for your service 
and some drivers using them. To handle which driver uses which car, 
they execute this application:

[https://little-taxi.herokuapp.com/](https://little-taxi.herokuapp.com/)

We know what driver **Vasyl** use 
  * login *vasyl* 
  * password *1234*
   
This is awful practice, please never do that! 
But we can use those credentials and figure out how 

# The application is used for:
  
  * Login and logout
  * Display list of all drivers
  * Display list of all cars
  * Display list of cars manufacturers
  * Create (register) a new driver account with name and license number
  * Delete driver from list
  * Create a new car with model and manufacturer
  * Delete car from list
  * Create new manufacturer with name and country
  * Delete manufacturer from list
  * Add some driver to some car
  * Display list of cars for current driver

Feel free to create cars, manufacturers and drivers. You can delete it too. Please, don't delete all of it, maybe someone else wants to use this useful application) If you want to become a hacker, you can try to bruteforce a credentials 
for other drivers. I think, it's the likes of Vasyl credentials)
But if you want to become a Java developer, like me, you will be interested in how the project work.

# Project description

Little taxi project realized in Java and HTML basics. All SOLID principles are used to create this program. Also was used this technologies: Java 11 JRE and Intellij IDEA as JDK, Apache Tomcat 9 as Webserver, MySQL 8 server as database management system and MySQL Workbench as a shell, Apache Maven 3.8 as development tool package, JSTL 1.2 as tag library, Java Servlet 4 as layer between HTTP protocol and Java program, Dependency Injector as inner program technology and a HTTP + CSS for presentation tier implementation.
Project implements three-layer based architecture:

  * **DAO** - data access Tier
  * **Service** - business Tier
  * **Controllers** - presentation Tier

# This is a database structure

![Tables](images/tables.jpg)

OK, you can use my code, it's open, to create your own application. To execute programs locally, begin by forking this project and downloading code from the forked repository

[Little taxi project](https://github.com/LowPassenger/little-taxi)

  * Must have: JDK (Intellij IDEA Ultimate, Eclipse e.t.c), Git, Apache Maven, Apache Tomcat, Apache log4j2, MySQL or any other server and (optionally) MySQL Workbench. Use guides and Google Search for troubleshooting apps installation issues.
  * Create a database, use init_db.sql from 
*src/main/resources/*
  * Set up a connection to the database, use credentials from SQL - login, password, path to your database and your JDBC driver in the ConnectionUtil.java file
*src/main/java/taxi/util/*
  * Add TomcatLocal to JDK configuration. Use default port 8080. Do not forget to specify a Tomcat installation folder and select taxi_service:war exploded in the fix window, also change the initial path from */web_security_war_exploded* to */* 
  * Configure the internal logger, use log4j2.xml file from
*src/main/resources/*
  * The standard path to log file is 
*logs/*
  * Perhaps you need to change it to an absolute path like "*D:/Projects/Taxi/logs/*"
  * Feel free to edit log messages and log levels for messages in your code. 


![123](images/123.jpg)![345](images/345.jpg)