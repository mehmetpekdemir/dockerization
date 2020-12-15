# Dockerization

### Dockerization of spring boot application

-----------------------

### Requirements

For building and running the application you need:
- [JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org)
- [Docker](https://www.docker.com/)

-----------------------

### Build & Run

mvn build ->
 - Main

   - Goals : clean compile install
   - Profiles : pom.xml
   - select Skip Tests

 - JRE
    - Alternate JRE: jdk-11.0.7

- Run


```
  docker-compose -f docker-compose.yml up -d
```

-----------------------

### Ports       
 ```
  application : http://localhost:8084/hello
  
  phpMyAdmin : http://localhost:8082/        
```

