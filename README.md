# Microservicio API Gateway

Este microservicio funciona como la puerta de entrada principal de la plataforma. Su tarea es recibir todas las peticiones desde el exterior y dirigirlas al microservicio correcto usando el directorio de Eureka. Además de distribuir solicitudes, protege el sistema evitando que alguien acceda directamente a los servidores internos.
## Dependencias
* Spring Cloud Gateway
* Eureka 
* Spring Security
* Spring Boot Starter 
* Lombok
