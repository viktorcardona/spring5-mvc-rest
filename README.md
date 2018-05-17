[![CircleCI](https://circleci.com/gh/viktorcardona/spring5-recipe-app.svg?style=svg)](https://circleci.com/gh/viktorcardona/spring5-recipe-app)
# Spring Framework 5 MVC Rest Application

This app comes from a Spring Framework 5 Online course [here.](http://courses.springframework.guru/p/spring-framework-5-begginer-to-guru/?product_id=363173)

Run:

    mvn spring-boot:run

VendorControllerTest

    Uses @WebMvcTest

CategoryController

    Uses old annotation @Controller (spring 2.5) and ResponseEntity (spring 3.0.2) for Rest Service

VendorController

    Uses @RestController (spring 4.0) more suitable for a Rest Service

Swagger:

    Swagger: support for Restful Documentation for each API
    Swagger Library: pom.xml: springfox-swagger2 (2.7.0), springfox-swagger-ui (2.7.0)
    Swagger Config: guru.springfamework.config.SwaggerConfig 
    Swagger Doc: http://localhost:8080/v2/api-docs
    Swagger-UI: http://localhost:8080/swagger-ui.html
    