# 4.1.-SpringFrameworkB_N1
This project is a simple Spring Boot application that demonstrates how to use REST controllers with path and request parameters.

## Features
- `/salute?nom=YourName`\
  This method will respond to GET requests.\
  Returns a greeting using the `nom` query parameter (default value: UNKNOWN) via @RequestParam.  
  It returns, for example, `Hola, nom. Estàs executant un projecte Maven.`

- `/salute2/{nom}`\
  This method will also respond to GET request.\
  Returns a greeting using the `nom` path variable. The parameter `nom` will be optional.  
  It returns, for example, `Hola, nom. Estàs executant un projecte Maven.`
  
## Requirements
- Java 17+
- Maven

## Links
- https://www.baeldung.com/spring-request-param
- https://www.baeldung.com/spring-optional-path-variables
