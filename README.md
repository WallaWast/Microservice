# Microservices Project

A simple microservices project to control a catalog

## Technologies

.Net 5, API, Swagger, MongoDb


## Running the application:

-   Download the database with the Docker command:
-   > docker run -d --rm --name mongo -p 27017:27017 -v mongodbdata:/data/db mongo
-   Go to the project folder "Play.Catalog.Service" and type `dotnet run`
-   Open the browse and go to the link: https://localhost:5001/
