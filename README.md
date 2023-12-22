Swapi Cache Engine

Overview:

The Swapi Cache Engine is a Spring Boot application designed to fetch and cache Star Wars data from the SWAPI (Star Wars API). This application uses a caching mechanism to improve performance by reducing redundant API calls.

Features:

Fetch and cache data for Characters, Films, Planets, Species, Starships, and Vehicles from SWAPI.
Caching mechanism implemented using SwapiCache for efficient data retrieval.

Technologies Used:

1. Java: Core programming language for the backend logic.
2. Spring Boot: Provides a framework for creating robust, scalable applications.
3. RESTful API: Design architecture for seamless data communication.
4. SWAPI (Star Wars API): Source of Star Wars-related data.
5. Caching: Leveraging SwapiCache for optimized data retrieval.


 Clone the Repository

 git clone https://github.com/shibam-max/ShibamSamaddarSwapiCacheEngine.git

Navigate to the Project Directory

cd ShibamSamaddarSwapiCacheEngine

Run the Application 

Follow the standard Spring Boot run procedure to launch the application.

API Endpoints:

Characters:

GET /api/characters: Get all characters.

GET /api/characters/{name}: Get character by name.

Films:

GET /api/films: Get all films.

GET /api/films/{title}: Get film by title.

Planets:

GET /api/planets: Get all planets.

GET /api/planets/{id}: Get planet by ID.

GET /api/planets/name/{name}: Get planet by name.

GET /api/planets/climate/{climate}: Get planets by climate.

Species:

GET /api/species: Get all species.

GET /api/species/{name}: Get species by name.

GET /api/species/lifespan/{lifespan}: Get species by lifespan.

Starships:

GET /api/starships: Get all starships.

GET /api/starships/{name}: Get starship by name.

Vehicles:

GET /api/vehicles: Get all vehicles.

GET /api/vehicles/{name}: Get vehicle by name.

GET /api/vehicles/model/{model}: Get vehicles by model.

GET /api/vehicles/manufacturer/{manufacturer}: Get vehicles by manufacturer.

Testing:

To test these endpoints, utilize tools like Postman to ensure that each endpoint functions as expected.

Test the API Endpoints:

To test the API endpoints, you can use tools like Postman. Below are the steps to test each endpoint:

Characters:

Get all characters:

URL: http://localhost:8083/api/characters

Get character by name:

URL: http://localhost:8083/api/characters/{name}

Films:

Get all films:

URL: http://localhost:8083/api/films

Get film by title:

URL: http://localhost:8083/api/films/{title}

Planets:

Get all planets:

URL: http://localhost:8083/api/planets

Get planet by ID:

URL: http://localhost:8083/api/planets/{id}

Get planet by name:

URL: http://localhost:8083/api/planets/name/{name}

Get planets by climate:

URL: http://localhost:8083/api/planets/climate/{climate}

Species:

Get all species:

URL: http://localhost:8083/api/species

Get species by name:

URL: http://localhost:8083/api/species/{name}

Get species by lifespan:

URL: http://localhost:8083/api/species/lifespan/{lifespan}

Starships:

Get all starships:

URL: http://localhost:8083/api/starships

Get starship by name:

URL: http://localhost:8083/api/starships/{name}

Vehicles:

Get all vehicles:

URL: http://localhost:8083/api/vehicles

Get vehicle by name:

URL: http://localhost:8083/api/vehicles/{name}

Get vehicles by model:

URL: http://localhost:8083/api/vehicles/model/{model}

Get vehicles by manufacturer:

URL: http://localhost:8083/api/vehicles/manufacturer/{manufacturer}



Steps to Test

Open Postman: Launch the Postman application on your local machine.

Select the HTTP Method: Choose the appropriate HTTP method (typically GET) from the dropdown menu.

Enter the URL: Use the specified URL patterns for each endpoint.

Send the Request: Click the "Send" button in Postman.

Review the Response: Verify the data returned aligns with the expected results for each endpoint.

Caching

The application utilizes the SwapiCache to cache fetched data. This ensures faster retrieval of data without making redundant API calls to SWAPI.


