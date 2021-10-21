<a id="up"></a>
#Taxi service web application
___This application is a simplified version of the taxi service.  
Created to demonstrate my software skills.___
##Contents
___
- [Technologies used](#technologies)
- [Features](#features)
- [How Start](#howStart)

##Technologies used
___
* __Java 11__
* __MySQL__
* __Servlet API__
* __JSTL__
* __Maven__
* __Tomcat 9.0.50__
* __SOLID concepts__  
  <a id="technologies"></a>

##Features
___
In order to gain access to all functions, 
you must add drivers (register) or authenticate.  
After that, you will be presented with such functions as:
* Adding a driver to the car
* Show a list of all drivers
* Show a list of all cars
* Add a new car  
* And much more :)
<a id="features"></a>
  
##How Start
___
* Install __MySQL__ or other DB
* Install __Tomcat 9.0.50__
* Fork and clone this project 
* Initialize your database using [__init_db.sql__](src/main/resources/init_db.sql) 
* Add your correct information to [___ConnectionUtil___](src/main/java/mate/util/ConnectionUtil.java) to be able to connect to your database

```java
    private static final String URL = "[YOUR DATABASE URL]";
    private static final String USERNAME = "[YOUR USERNAME]";
    private static final String PASSWORD = "[YOUR PASSWORD]";
    private static final String JDBC_DRIVER = "[YOUR DRIVER]";
```
* Run this project using __Tomcat's__ local server
<a id="howStart"></a>
---  

[UP](#up)