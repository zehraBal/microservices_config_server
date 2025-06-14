# Config Server

[GitHub] (https://github.com/zehraBal/Microservices/tree/main/Offline_Microservice/E_Commerce_Platform/Config_Server/config_server)

## Config Server

- Mikroservislerin konfigürasyonlarını merkezi bir yerde yönetmek için kullanılan yapıdır.

# Spring Cloud (Config Client)

- Spring Cloud Server'dan konfigürasyonları almak için kullanılan istemcidir.
- Mikroservisler genellikle Config Client olarak yapılandırılır.
- Config Client, Config Server'a bağlanır ve merkezi olarak yönetilen konfigürasyon dosyalarını alır.
- Uygulama merkezi olarak yönetilen konfigürasyonları almak için Spring Cloud Config Server'a bağlanacaksa Config Client eklenir.

# Spring Cloud (Config Server)

- Merkezi bir konfigürasyon yönetimi sunucusudur.
- Bir veya daha fazla mikroservisin konfigürasyon dosyalarını merkezi bir yerde sunar.
