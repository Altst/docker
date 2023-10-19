# Vue.js, Node.js, MySQL with Docker

This is a Docker Compose setup for creating and executing a web application consisting of a Vue.js Vite frontend and a Node.js, MySQL backend.

## Prerequisites

Prior to starting, please ensure that you have Docker and Node.js installed on your system.

## Installation and Usage

1. Clone this repository:

   ```shell
   git clone https://github.com/Altst/docker.git
   cd docker

2. Install Node.js Modules

    npm i

3. Build the Docker images:

    docker-compose build

4. Start the containers:

    docker-compose up

You can access the frontend at http://localhost:5000, and the backend will be accessible at http://localhost:8081.

## Open Database

1. In order to establish a connection with the database, please navigate to the following port: http://localhost:8080. You will then be directed to the ADMINER database management environment.

2. You must log in using this set of credentials:
    System: MySQL
    Server: msql
    Username: user1
    Password: 1111
    Database: DockerDB

3. You have the option to add or remove fields through the interface.

## Stop Database

    docker-compose stop

Upon re-entering the image, the data in the database will be stored.