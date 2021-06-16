# Microservices Project

A simple microservice

## Technologies

.Net 5, API, Swagger, MongoDb, RabbitMq, Oauth2, Identity

## PUT the Admin Password on the secret storage
dotnet user-secrets set "IdentitySettings:AdminUserPassword" "PASSWORD_HERE"

## Running the application:

-   Initialize the Database on the PLAY.INFRA project running the command:
-   > docker-compose up -d
-   Go to the project folder "Play.Catalog.Service" and type `dotnet run`
-   Open the browse and go to the link: https://localhost:5001/
