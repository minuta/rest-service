# Spring REST Webservice

### About
A simple web service with a REST endpoint, that returns a JSON object on a HTTP GET.

The REST service can consume a parameter "name"

### Techstack
* Java 11
* Spring Boot : 2.4.4
* Maven Wrapper
* Spring Initializer : https://start.spring.io/
* Tomcat

### Usage
```sh
./mvnw spring-boot:run
```


http://localhost:8080/greeting

http://localhost:8080/greeting?name=foo

```sh
curl http://localhost:8080/greeting
```

It will respond with a JSON representation of a greeting, as the following listing shows:

```json5
{"id":1,"content":"Hello, World!"}
```

---

based on:

* https://spring.io/guides/gs/rest-service/
* https://start.spring.io/