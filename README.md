# Findest Project

Welcome to the Findest project! This project is designed to simplify the deployment and execution of an application using Docker. Follow the steps below to extract the source code, build the necessary Docker containers, and launch the application.

## Prerequisites

Make sure you have the following tools installed on your machine:

- Docker
- Maven
- JDK (Java Development Kit)

## Installation Instructions

### Downloading the Source Code

Clone the GitHub repository to your local machine using the following command:

git clone https://github.com/your-username/findest-project.git

cd servapp

### Building Docker Containers
Navigate to the servapp directory and run the following commands to build the Docker containers:

docker compose build

### Launching Docker Containers
Once the containers are built, start them with the command:

docker-compose up


## Running the Application Locally
### Maven Configuration
Ensure that Maven is added to your PATH:

set PATH="path-to-apache-maven-3.9.6/bin:$PATH"
Maven is available in the GitHub repository.

### Launching the Application with Maven
In the findest directory, use the following command to run the application with Maven:

cd findest
mvn spring-boot:run

The application should now be accessible at http://localhost:8080.
