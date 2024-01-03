# Jomo Website Spring Boot Application

This project will provide separate Technology based capabilities & Functional services:
1. Web Based Spring Boot Application that uses Java Spring Boot, running an embedded Tomcat App server, executed as JAR Java Application 

The project is built using Java 8, Spring Boot, StyleShout template

## Credits and related project
This Project is build using few resources:
1. StyleShout Web templates - https://www.styleshout.com

2. Simple Spring class wrapper

3. Jomo Static Web site - for rendering ReadMe.md documentation images from external website: https://github.com/alexilie/jomo-static-website


## Table of Contents
* [Prerequisites](#prerequisites)
* [Libraries](#libraries)
* [Running the application](#running-the-application)
    * [On Windows](#on-windows)
    * [On Mac](#on-mac) - to do
* [Database user](#database-user)
* [Screens](#screens)

## Prerequisites
- [Java JDK](https://www.oracle.com/pl/java/technologies/javase-downloads.html) version 8+
- Java JRE 8+
- Maven 
- GitHub
- Git client (command line tool)
- IntelliJ 
- Eclipse (Optional) 
- VisualSource Code (Optional) 
- GitHub Desktop (optional)
- Windows OS or Mac OS  based computer/ laptop

## Libraries
| Library name                                                                                                     | Description                                                                                                                          |
|------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| [Spring Boot 2](https://spring.io/projects/spring-boot)                                                          | Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run".                 |
                                                            
## Getting the application source and files from GitHub; build local project
1. Go to the following GitHub project https://github.com/alexilie/jomo-website
2. Copy the Git project using "git clone" command ...> got clone https://github.com/alexilie/jomo-website.git

## GitHub project  | screen
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-1.PNG "Screen 1")

3. Create a local working folder (if not available); for example purpose we will use working folder "Projects" e.g. C:\Projects

4. Open a Windows Command line program; change directory to intended C:\Projects folder - > cd C:\Projects

5. From Windows CMD; Copy the Github "jomo-website" project repository using Git "clone" command > C:\Projects> git clone https://github.com/alexilie/jomo-website.git
## Git Clone command  - copy repository | screen
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-2.PNG "Screen 2")

6. After "Git clone" command is executed, a new folder "jomo-website" will be automatically created in the working "Projects" folder

7. Change directory to the new created folder "jomo-website" > cd jomo-website

* Observation - GitHub repository can be downloaded as ZIP archive as well; or can be downloaded using GitHub desktop or any other Git Client 

8. Build "jomo-website" project by executing Maven build "mvn clean install" command-  C:\Projects\jomo-website > mvn clean install

* Observation - you can open the "jomo-website" project in Intellij - start IntelliJ, Open Project from "jomo-website" folder, 
then alternatively you can build the "jomo-website" project from inside Intellij CMD Terminal window, or launch the build using Maven build task 


## Maven build command | screen
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-3.PNG "Screen 3")

![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-4.PNG "Screen 4")

## Maven build command | screen
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-5.PNG "Screen 5")

9. Open IntelliJ IDE (if not done yet)
   open Project from following location C:\Projects\jomo-website > mvn clean install
## IntelliJ IDE jomo-metamodel-web App | screen
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-7.PNG "Screen 7")

8. Maven build  will generate auto-executable "jomo-website-app-0.0.1-SNAPSHOT" JAR Java archive in the "target" build subfolder
## Maven build artifacts in target folder  | screen
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-6.PNG "Screen 6")

## Running the Spring-boot jomo-website as Web App inside Tomcat App server
#### On Windows

9. To execute from Windows CMD line or IntelliJ Terminal command window use Maven run command: > mvn spring-boot:run 
you can use any of the the Maven commands 
```
C:\Projects\jomo-website > mvn spring-boot:run

C:\Projects\jomo-website > mvnw.cmd spring-boot:run

C:\Projects\jomo-website > java -jar target/jomo-website-app-0.0.1-SNAPSHOT.jar

C:\Projects\jomo-website\target > java -jar jomo-website-app-0.0.1-SNAPSHOT.jar 
```

the Maven command "mvn spring-boot:run" will start Tomcat App Server on (default) port 8080, 
then will deploy the "jomo-website-app-0.0.1-SNAPSHOT.jar" JAR in the Tomcat embedded server

## Maven command to run and execute the application | screen 
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-8.PNG "Screen 8")
## Maven command to run and execute the application | screen 
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-9.PNG "Screen 9")
## Maven command to run and execute the application | screen 
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-10.PNG "Screen 10")
## Maven command to run and execute the application | screen 
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-11.PNG "Screen 11")

## Runnning the Jomo Website Web application as SpringBoot App | screen

Home page: http://localhost:8080/
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-38.PNG "Screen 38")

Accessing Application menu: http://localhost:8080/
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-39.PNG "Screen 39")

View Applications: http://localhost:8080/applications
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-40.PNG "Screen 40")

Update existing application: http://localhost:8080/applications-edit/6
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-41.PNG "Screen 41")

Add new application: http://localhost:8080/applications-new
![alt text](https://main.d37vqs13py7d1c.amplifyapp.com/images/metamodel/jomo-metamodel-web-img-42.PNG "Screen 42")


## Accessing the Jomo Website Application
| Resource        |  URL         	                                     |          |
|------------------------------------------------------------------------|----------|---------- |
| App Home         | http://localhost:8080                               | 

