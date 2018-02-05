# Spring Boot Playground

This is just a repository where I play around with spring boot.

It has been generated with the following command:

`spring init --dependencies=actuator,data-jpa,h2,thymeleaf,web spring-boot-playground`

# Install Dependencies

Run the following command in order to install the dependencies:

`mvn install`

# Run it

`./mvnw spring-boot:run`

If everything went fine, you can see the index page visiting the following URL on your browser:

`http://localhost:8000/`

# Clean dependencies

`mvn dependency:purge-local-repository`
