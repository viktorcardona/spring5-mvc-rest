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
    Swagger Doc: in JSON format: http://localhost:8080/v2/api-docs
        The published JSON could be copy and paste in the online Swagger editor: https://editor.swagger.io/ and see the HTML format generated
        There is also a desktop version of the Swagger editor
        The swagger web site also gives the choice of generating the code server and client in multiple languages  
    Swagger-UI: Doc in HTML format: http://localhost:8080/swagger-ui.html
    