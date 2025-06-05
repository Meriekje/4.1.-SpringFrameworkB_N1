# 4.1.-SpringFrameworkB_N1
This project is a simple Spring Boot application that demonstrates how to use REST controllers with path and request parameters.

## Features
- `/salute?nom=YourName`  
  Returns a greeting using the `nom` query parameter.  
  Example: `Hola, Sergi. Estàs executant un projecte Maven.`

- `/salute2/{nom}`  
  Returns a greeting using the `nom` path variable.  
  Example: `/salute2/Sergi` returns `Hola, Sergi. Estàs executant un projecte Maven.`

**Access the endpoints:**
   - [http://localhost:9000/salute?nom=Sergi](http://localhost:9000/salute?nom=Sergi)
   - [http://localhost:9000/salute2/Sergi](http://localhost:9000/salute2/Sergi)

## Requirements
- Java 17+
- Maven
