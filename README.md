# Setting up of PostgreSQL using official docker image
This repository is used for setting up a working postgres using the official postgres docker image file.

## Setup
- [Postgres 10.4](https://hub.docker.com/_/postgres/ "Postgres Official Docker Image")
- Docker 18.05.0-ce 
- Docker-compose 1.21.2

## Running it
- Pull the official image from postgres
    - `docker pull postgres:10.4`
- With the docker-compose file in the same directory,
    - To start, `docker-compose up -d` 
    - To stop, `docker-compose down `