# Achievement Service

# Technologies Used

* [Spring Boot](https://spring.io/projects/spring-boot) – Primary framework
* [PostgreSQL](https://www.postgresql.org/) – Main Relational DataBase
* [Redis](https://redis.io/) – Used for caching and message queuing via pub/sub
* [Liquibase](https://www.liquibase.org/) – Manages database schema migrations
* [Gradle](https://gradle.org/) – Build system for the application
* [Lombok](https://projectlombok.org/) – Work with POJO classes
* [MapStruct](https://mapstruct.org/) – Mapping between POJO classes

# DataBase

* The database is launched in a separate service [infra](../infra)
* Redis is also started as a single instance in infra infra [infra](../infra)
* Liquibase automatically applies necessary migrations to a fresh PostgreSQL instance on application startup
