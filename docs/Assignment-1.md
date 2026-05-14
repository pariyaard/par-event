# Assignment 1

## Running the application

Docker support was added to the project by creating:
- a Dockerfile
- a docker-compose.yml file

The application was started locally with Docker.

The project was started with:

```text
docker compose up --build
```

The application runs on:

```text
http://localhost:8080
```

A Postman collection was added to show the API requests.

Location:

```text
docs/postman/Event Planner API.postman_collection.json
```


## Current application
The current application is a backend event planner application.

The application allows users to:
- create users
- update users
- delete users
- create events
- update events
- delete events
- cancel events

The application uses a layered structure with:
- controllers
- services
- repositories
- DTOs
- entities

The backend is built with:
- Spring Boot
- Java 21
- Hibernate / Spring Data JPA
- H2 in-memory database

There is a relationship between users and events.
One user can have multiple events.


## Company and project goal
Company name:
EventFlow

The goal of the project is to improve the current event planner application into a more scalable platform.

The platform can be used by:
- small companies
- schools
- student teams
- organizations

The current application already supports users and events.

In future assignments the system can be improved by splitting the application into smaller parts and improving the communication between systems.

The goal is to create a better structured and scalable system.


## Future improvements
In future assignments the application can be improved by:
- splitting the system into smaller parts
- improving communication between systems
- improving scalability
- improving the structure of the application
- improving event management functionality

The project will focus on creating a better distributed and scalable system.


## Quality requirements
The project should focus on:
- scalability
- maintainability
- clear system structure
- better communication between systems
- reliability

The goal is to create a system that is easier to maintain and improve in future assignments.
