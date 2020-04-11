**UPDATE**: The price of "Learn Spring Security OAuth" will permanently change on the 11th of December, along with the upcoming OAuth2 material: http://bit.ly/github-lss

The Courses
==============================


Here's the new "Learn Spring" course: <br/>
**[>> LEARN SPRING - THE MASTER CLASS](https://www.baeldung.com/learn-spring-course?utm_source=github&utm_medium=social&utm_content=tutorials&utm_campaign=ls#master-class)**

Here's the Master Class of "REST With Spring" (along with the new announced Boot 2 material): <br/>
**[>> THE REST WITH SPRING - MASTER CLASS](https://www.baeldung.com/rest-with-spring-course?utm_source=github&utm_medium=social&utm_content=tutorials&utm_campaign=rws#master-class)**

And here's the Master Class of "Learn Spring Security": <br/>
**[>> LEARN SPRING SECURITY - MASTER CLASS](https://www.baeldung.com/learn-spring-security-course?utm_source=github&utm_medium=social&utm_content=tutorials&utm_campaign=lss#master-class)**



Java and Spring Tutorials
================

This project is **a collection of small and focused tutorials** - each covering a single and well defined area of development in the Java ecosystem. 
A strong focus of these is, of course, the Spring Framework - Spring, Spring Boot and Spring Security. 
In additional to Spring, the modules here are covering a number of aspects in Java. 


Building the project
====================
To do the full build, do: `mvn clean install`


Building a single module
====================
To build a specific module run the command: `mvn clean install` in the module directory


Running a Spring Boot module
====================
To run a Spring Boot module run the command: `mvn spring-boot:run` in the module directory


与 IDE 协同进行工作
====================
本仓库中包含有大量的模块。 
When you're working with an individual module, there's no need to import all of them (or build all of them) - you can simply import that particular module in either Eclipse or IntelliJ. 


运行测试
=============
运行 `mvn clean install` 将会在模块中运行单元测试（unit tests）。
如果你希望运行整合测试（integration tests），请使用命令 `mvn clean install -Pintegration-lite-first`




