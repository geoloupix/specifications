# Specifications

The specifications of the geoloupix project.

## Main objectives of the project

For our last year of high school, we have a project to realize in Computer Science. We chose to create a mobile application about geolocations.

Here is the goal: the user can easily save and organize locations in categories, following a file explorer like structure (involving recursion). Locations can be viewed and interacted with on a map. The user can also share it with other users.

Well that's the theory but most of those features are not implemented yet, because we lacked time. For the full list, see [this](https://github.com/geoloupix/app#available-features).

## Preparation

Before coding the application, we took some time to prepare and think about the project. Here is the list of the features we agreed on:

- Geolocalize the user
- Saving and organizing locations (using a CRUD (Create, Read, Update, Delete) system)
- The user stays connected through sessions by saving an API token offline
- An online database
- An authentication system
- Sharing system if we have the time.

We also decided to do a landing page but once again, due to lack of time, we only implemented a basic one. [View](https://geoloupix.fr).

API documentation can be seen [here](https://developers.geoloupix.fr).

Concerning the API, we decided to go with a RESTful API using Laravel. Available routes are listed [here](https://developers.geoloupix.fr/intro/api-reference#roadmap).

Finally, we also decided to create mockups for the mobile app before actually coding it. More info [here](https://github.com/geoloupix/app#introduction)

## Tasks and repartition

We did a basic repartition of tasks. Each one had to implement features on its side (data handling / user interface). We ended up with the following _global_ tasks:

| Task          | Responsible |
| ------------- | ----------- |
| API (Laravel) | Marc        |
| App (Flutter) | Florian     |
