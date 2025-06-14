# Config Server

[GitHub] (https://github.com/zehraBal/microservices_config_server)

## Config Server

- It is a structure used to manage the configurations of microservices in a centralized manner.

# Spring Cloud (Config Client)

- It is the client used to retrieve configurations from the Spring Cloud Config Server.
- Microservices are typically configured as Config Clients.
- The Config Client connects to the Config Server and retrieves centrally managed configuration files.
- If the application needs to connect to the Spring Cloud Config Server to obtain centrally managed configurations, a Config Client is added.

# Spring Cloud (Config Server)

- It is a centralized configuration management server.
- It serves the configuration files of one or more microservices in a central location.
