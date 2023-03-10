# **Taxi-Service**
___
## Project description:
A simple wed-application that supports authentication,
registration and other CRUD operations.

___
### For whom and why this program is needed. Basic functions.

This project was created for small businesses that need to manage 
cars with fixed drivers for them. There are no extra functions in 
the program. Anyone can learn to use the program in 2 hours.
All your data is stored in a database locally on your computer

* create/update/remove a car;
* create/update/remove a driver;
* create/update/remove a manufacturer;
* registration like driver;
* authentication like driver;
* display list of all cars;
* display list of all drivers;
* display list of all manufacturers;
* add drivers to cars;
* the program starts on the local server;
* the program works with a local database;

### Structure of APP
DAO <=> Services <=> Controllers
___
### The following technologies were used in the project
* Java 11; [downland](https://www.oracle.com/cis/java/technologies/javase/jdk11-archive-downloads.html)
* Git 2.2.0; [downland](https://git-scm.com/downloads)
* Apache Maven 4.0.0; [downland](https://maven.apache.org/download.cgi)
* Apache Tomcat 9.0; [downland](https://tomcat.apache.org/download-90.cgi)
* MySQL; [downland](https://www.mysql.com/downloads/)
* JDBC;
* Javax Servlet;
* JSP;
* JSTL;
* HTML/CSS;
* Apache Maven Checkstyle Plugin 3.1.1;
* Project Lombok;
* Intellij IDEA Ultimate [downland](https://www.jetbrains.com/idea/download/#section=windows)
* MySQL Workbench [downland](https://dev.mysql.com/downloads/workbench/)

___
### How to start the program
1. Download all programs
2. Clone the project from GitHub
3. Create new project form Version Control in Intellij IDEA 
4. Use /resources/init_db.sql to create a database in MySQL Workbench
5. Configure /util/ConnectionUtil.java with your own URL, username, password and JDBC driver
6. Configure Tomcat server (IMPORTANT 9 version)

___

![taxi service](https://img.freepik.com/free-vector/taxi-service-logo-template_1057-4799.jpg?w=740&t=st=1673885682~exp=1673886282~hmac=6e19ce340bd86efdd6f327764e14322e00417c883eded9577fe31a2f242c26a0)