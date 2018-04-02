# Learn Microservices with Spring Boot - v7

This project contains the version 8 of the application that is developed under the scope of the book *Learn Microservices with Spring Boot*. You can get a copy of the book on [Amazon](http://amzn.to/2FSB2ME) or [Apress](http://www.apress.com/book/9781484231647).

The book shows you how to evolve a simple Spring Boot application to become a full Microservices Architecture, using Spring Cloud Eureka, Ribbon, Zuul and Hystrix to implement Service Discovery, Load Balancing, the API Gateway pattern and a Circuit Breaker. Besides, you'll learn how to implement End-to-End tests with Cucumber, an Event-Driven system and the best practices when building Microservices.

## About this version

This version contains three projects: 
* **gamification** and **social-multiplication** are our microservices already created and evolved in previous versions. 
* **ui** contains the web pages and javascript of our application, within an independently deployable component.
* **gateway** contains the new Spring Boot Application that models the API Gateway in our system, using Zuul.


# Docker
docker run -d --hostname my-rabbit --name some-rabbit -p 15671:15671 -p 15672:15672  -p 25672:25672   -p 4369:4369  -p 5671:5671 -p 5672:5672   rabbitmq:3-management
<br/>
default user,password ( guest guest  )

頁面是管理頁面(15672頁面是不錯的選擇)
不然用他的CLI指令，搭配Python下指令
https://www.rabbitmq.com/management-cli.html
python.exe rabbitmqadmin.
