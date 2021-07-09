# SpringCloudZuul

## Description
Project that show how to implement a reverse proxy using the Spring Cloud Netflix Zuul.

## Technologies
The project use the following technologies:

* Java 11
* Apache Maven
* Project aggregation
* Spring Boot
* Spring Cloud Netflix Eureka
* Spring Cloud Netflix Zuul
* IDE Eclipse

## Testing the project
**Step 1:** Start the microservices
* EurekaServer
* ZuulServer
* ServiceOne
* ServiceTwo

**Step 2:** Access the microservices using the reverse proxy port:

```
http://localhost:8765/serviceone/serviceone
http://localhost:8765/servicetwo/servicetwo
```

**Tip:** The routes of reverse proxy are configured in **application.properties** file.

## Release History
* 1.0.0 (2021-05-15)
    * First version
