# microservice-1
Limits microservice. Example of centralized configuration using Spring Cloud Config Server.

Dependencies:
1. Spring Web
2. Spring Boot DevTools
3. Spring Boot Actuator
4. Config Client (Client that connects to a Spring Cloud Config Server to fetch the application's configuration)
5. Config Server (Central management for configuration via Git, SVN, or HashiCorp Vault)

Ports:
limits-microservice : 8080, 8081,....
spring-cloud-config-server : 8888
