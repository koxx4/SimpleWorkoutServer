Backend server written made using [**SpringFramework**](https://spring.io/). It exposes REST endpoints allowing frontend [SimpleWorkout](https://github.com/koxx4/SimpleWorkOut) to save users, their data and retrieve it. Authentication is based on **JWS tokens** and database credentials are held in [secret vault by HashiCorp](https://www.vaultproject.io/). Database (MariaDB) hosted on AWS, server on DigitalOcean.

[API Docs](https://sws-server.koxx4.me:8080/swagger-ui/)
