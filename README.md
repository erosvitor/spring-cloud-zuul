## About
The project shows how to implement a reverse proxy using the Spring Cloud Netflix Zuul.

## Technologies
The following tools were used in this project:

* [Java Oracle](https://www.oracle.com/java/)
* [Apache Maven](https://maven.apache.org/)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Cloud Netflix Eureka](https://spring.io/projects/spring-cloud-netflix)
* [Spring Cloud Netflix Zuul](https://spring.io/projects/spring-cloud-netflix)
* [IDE Eclipse](https://www.eclipse.org/)

## Requirements
Before starting this project you need to have Git, JDK Oracle, Maven and Eclipse IDE installed.

## Starting the project

### Clonning the project
```
$ git clone https://github.com/erosvitor/spring-cloud-zuul.git

$ cd spring-cloud-zuul
```

### Testing the project
**Step 1:** Start the application using Eclipse IDE or by Maven command line
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

## License
This project is under license from MIT. For more details, see the LICENSE file.

## Release History
* 1.0.0 (2021-05-15)
    * First version
