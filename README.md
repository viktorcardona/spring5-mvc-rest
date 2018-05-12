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
