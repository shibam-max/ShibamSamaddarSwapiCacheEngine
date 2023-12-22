Swapi Cache Engine

Overview

The Swapi Cache Engine is a Spring Boot application designed to fetch and cache Star Wars data from the SWAPI (Star Wars API). This application uses a caching mechanism to improve performance by reducing redundant API calls.

Features

Fetch and cache data for Characters, Films, Planets, Species, Starships, and Vehicles from SWAPI.
Caching mechanism implemented using SwapiCache for efficient data retrieval.

Technologies Used

1. Java: Core programming language for the backend logic.
2. Spring Boot: Provides a framework for creating robust, scalable applications.
3. RESTful API: Design architecture for seamless data communication.
4. SWAPI (Star Wars API): Source of Star Wars-related data.
5. Caching: Leveraging SwapiCache for optimized data retrieval.

1. Clone the Repository

git clone https://github.com/shibam-max/ShibamSamaddarSwapiCacheEngine.git

2. Navigate to the Project Directory

cd ShibamSamaddarSwapiCacheEngine

3. Run the Application 

Follow the standard Spring Boot run procedure to launch the application.

API Endpoints

Characters

GET /api/characters: Get all characters.

GET /api/characters/{name}: Get character by name.

Films

GET /api/films: Get all films.

GET /api/films/{title}: Get film by title.

Planets

GET /api/planets: Get all planets.

GET /api/planets/{id}: Get planet by ID.

GET /api/planets/name/{name}: Get planet by name.

GET /api/planets/climate/{climate}: Get planets by climate.

Species
GET /api/species: Get all species.

GET /api/species/{name}: Get species by name.

GET /api/species/lifespan/{lifespan}: Get species by lifespan.

Starships
GET /api/starships: Get all starships.

GET /api/starships/{name}: Get starship by name.

Vehicles
GET /api/vehicles: Get all vehicles.

GET /api/vehicles/{name}: Get vehicle by name.

GET /api/vehicles/model/{model}: Get vehicles by model.

GET /api/vehicles/manufacturer/{manufacturer}: Get vehicles by manufacturer.

Testing

To test these endpoints, utilize tools like Postman to ensure that each endpoint functions as expected.

Caching

The application utilizes the SwapiCache to cache fetched data. This ensures faster retrieval of data without making redundant API calls to SWAPI.


