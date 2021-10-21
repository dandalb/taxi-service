<a id="up"></a>

<h1>Taxi service web application</h1>   

___This application is a simplified version of the taxi service. Created to demonstrate my software skills in Java.___

<h2>Contents</h2>

- [Technologies used](#technologies)
- [Features](#features)
- [How Start](#howStart)

<a id="technologies"></a>

<h2>Technologies used</h2>

* __Java 11__
* __MySQL__
* __Servlet API__
* __JSTL__
* __Maven__
* __Tomcat 9.0.50__
* __SOLID concepts__

<h2>Features</h2>

<a id="features"></a>

In order to gain access to all functions,
you must add drivers (register) or authenticate.  
After that, you will be presented with such functions as:
* Adding a driver to the car
* Show a list of all drivers
* Show a list of all cars
* Add a new car
* And much more :)

<h2>How Start</h2>

<a id="howStart"></a>

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

[UP](#up)
