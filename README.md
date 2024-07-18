# 🎟️ VotacaoCRUD BackEnd

As you can see in the title above, this project is the API that revolves about a voting system.

The voting system has agendas and users that can vote in these agendas.

## Table of Contents
- [✨ Running the Project](#running-the-project)
- [🏗️ Developing the Project](#developing-the-project)
- [📄 License](#license)

## Running the Project

To run the the back end is simple.

You can simply run the commands related to gradle wrapper.

- First run a ./gradlew build to build the project

- And after that run the ./gradlew bootRun to run the project

After that you have some options to test it:

- You can run the FrontEnd Project - If it's already developed
- You can go to http://localhost:8080/swagger-ui/index.html to see the Swagger documentation
- Or simply create a Http Request on your favorite API Client

## Developing the Project

This topic refers to all the technologies used in the project and the steps to build it using them.

### Technologies

- ☕ Java
- 🍃 Spring Boot
    - 📦 Spring Boot JPA
- 🌶️ Lombok
- 🧪 JUnit 5
- 🐋 Docker
- 🐘 PostgreSQL
- 🛠️ Swagger

### US's - MPV

- 🚧 [US000] Configure Repository
  - ✅ [US000-1] Implements a README
  - ✅ [US000-2] Configure GitHub Actions
- ✅ [US001] Configure Project
  - ✅ [US001-1] Create a Postgres Container
  - ✅ [US001-2] Configure JPA
  - ✅ [US001-3] Swagger Implementation
- ✅ [US002] Create Database
  - ✅ [US002-1] Create User Entity
  - ✅ [US002-2] Create Agenda Entity
  - ✅ [US002-3] Create Log Entity
- ✅ [US003] User Flow
  - ✅ [US003-1] Create Request and Response User DTO  
  - ✅ [US003-2] Create User
  - ✅ [US003-3] Implement Login Feature
- ✅ [US004] Agenda Flow
  - ✅ [US004-1] Create Request and Response Agenda DTO 
  - ✅ [US004-2] Create Agenda
  - ✅ [US004-3] Implements Agenda Start, Duration and End
  - ✅ [US004-4] Implement User Vote in Agenda
- ✅ [US005] Implement Log Population
  - ✅ [US005-1] Create Response Log DTO and Mapper
  - ✅ [US005-2] Implement Methods Related to User
  - ✅ [US005-3] Implement Methods Related to Agenda
- ✅ [US006] Error Treatment
  - ✅ [US006-1] Implement ErrorHandlers that are Related to User
  - ✅ [US006-2] Implement ErrorHandlers that are Related to Agenda
  - ✅ [US006-3] Implement ErrorHandlers that are Related to Log
- ✅ [US007] Test Implementation
  - ✅ [US007-1] Unitary Tests - Happy
  - ✅ [US007-2] Unitary Tests - Sad

### US's - Extra

- 🚧 [US00X] Related to Extra Features
  - 🚧 [US00X-1] Swagger Implementation
  - 🚧 [US00X-3] Integration Tests - Happy
  - 🚧 [US00X-4] Integration Tests - Sad
  - 🚧 [US00X-5] Performance Tests 

### Fix

- ✅ [Fix] Related to fix or merge missing features in dev branch
  - ✅ [fix-1] Add getUser method
  - ✅ [fix-2] Change way that methods validate User


## License
This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.
