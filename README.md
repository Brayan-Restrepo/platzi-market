# platzi-market

### Crear proyecto spring
https://start.spring.io/

### Application Properties
https://docs.spring.io/spring-boot/docs/current/reference/html/application-properties.html#appendix.application-properties.core

### Documentación Java
* https://www.geeksforgeeks.org/double-colon-operator-in-java/?ref=gcse

### Programación Orientada a Objetos
https://ferestrepoca.github.io/paradigmas-de-programacion/poo/poo_teoria/concepts.html

### Java Money and the Currency API

https://www.baeldung.com/java-money-and-currency


## Compliar app

java -jar .\build\libs\platzi-market-1.0.jar
java -jar "-Dspring.profiles.active=pdn" .\build\libs\platzi-market-1.0.jar


### Docker de postgres
    docker run --name basic-postgres --rm -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -e PGDATA=/var/lib/postgresql/data/pgdata -v /tmp:/var/lib/postgresql/data -p 5432:5432 -it postgres:14.1-alpine

### Estructura
    https://drive.google.com/file/d/1DZTGB-BC3LqoZLN_UK8uyt4_eZP-MfBl/view
#### Data
    https://drive.google.com/file/d/1MhNMwcxSvRYNfA8H3NjOtixSPM6Ovwaa/view