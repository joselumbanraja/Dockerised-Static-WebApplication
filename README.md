# Dockerised Static Web Application

This project demonstrates how to containerize a static web application using Docker and Nginx.

## Technologies Used

* Docker
* Docker Compose
* Nginx
* HTML

## Project Structure

```
dockerised-static-web
│
├── Dockerfile
├── docker-compose.yaml
├── index.html
└── img/profile.png
```

## Run Locally

Clone the repository:

```
git clone https://github.com/username/dockerised-static-web.git
```

Run the container:

```
docker compose up --build
```

Open in browser:

```
http://localhost:8080
```

## Description

The application is containerized using Docker and served using an Nginx web server.
Docker Compose is used to simplify container orchestration and port mapping.
