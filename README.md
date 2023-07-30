# Microservices with CQRS example

Example of a microservice with CQRS architecture implemented using RabbitMQ as message broker to process the events that happen in the microservices.

## Setup

1. Execute "git submodule update --init" command to clone the submodules.
2. Execute "npm run install" command to install the node modules for each sub module.
3. Execute "docker-compose up -d" command start the containers.

## Usage

There are two APIs to use, one is for handling product order commands (http://localhost:3001/swagger/), and the other to handle product order queries (http://localhost:3002/swagger/).
