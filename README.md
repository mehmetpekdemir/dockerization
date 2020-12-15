# Dockerization

### Dockerization of spring boot application

-----------------------

mvn build ->
 - Main

   - Goals : clean compile install
   - Profiles : pom.xml
   - select Skip Tests

 - JRE
    - Alternate JRE: jdk-11.0.7

- Run

-----------------------

docker-compose -f docker-compose.yml up -d

-----------------------

ports : 
 - application : http://localhost:8084/hello
 - php my admin : http://localhost:8082/        
