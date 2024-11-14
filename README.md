# Containers Workshop 

## Objective

The Objective of this workshop is to create a Dockerfile for your webapp and run it alongside your database using Docker Compose

## Instructions

1) Install Docker on your local machine https://docs.docker.com/engine/install/

2) The repository contains sample Docker files for an application

3) Use the respective Dockerfile and modify it according to your application

4) Build the docker image using the following command:
```bash
docker build -t <image-name> .
```

5) Run the docker image using the following command to test the application locally:
```bash
docker run -d -p 8080:8080 <image-name>
# ensure to change the port mapping according to your application
```

6) After testing the application locally, select a docker compose file and modify the environment variables according to your application

7) Run the docker compose file using the following command:
```bash
docker-compose -f <docker-compose-file> up
```

8) The Application should be running locally and it should be connected to your database running in a separate container


## Docker CLI Commands Cheatsheet 
https://docs.docker.com/get-started/docker_cheatsheet.pdf