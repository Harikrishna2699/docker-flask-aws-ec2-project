# Dockerized Flask Application on AWS EC2

## Project Overview
This project demonstrates how to containerize and deploy a Python Flask application using Docker on an AWS EC2 Ubuntu Linux server.

## Technologies Used
- AWS EC2
- Ubuntu Linux
- Docker
- Python
- Flask
- Gunicorn
- Git and GitHub

## Project Architecture

Developer → GitHub → Docker Image → Docker Container → Flask Application

## Project Implementation

1. Launched an Ubuntu EC2 instance.
2. Installed and configured Docker.
3. Pulled and deployed an Nginx container.
4. Developed a Python Flask application.
5. Created a Dockerfile.
6. Built a custom Docker image.
7. Deployed the Flask application inside a container.
8. Configured port mapping.
9. Used Gunicorn as the application server.
10. Created a `.dockerignore` file.
11. Created and tested Docker volumes.
12. Verified application health using a health endpoint.

## Important Docker Commands

| Command | Purpose |
|---|---|
| `docker pull` | Download an image |
| `docker images` | List images |
| `docker build` | Build an image |
| `docker run` | Create and start a container |
| `docker ps` | List running containers |
| `docker logs` | Check container logs |
| `docker exec` | Execute commands inside a container |
| `docker stop` | Stop a container |
| `docker rm` | Remove a container |
| `docker volume create` | Create a volume |
| `docker volume ls` | List volumes |
| `docker inspect` | Inspect Docker resources |

## Application Endpoints

- `/` – Application welcome page
- `/health` – Application health-check endpoint

## Learning Outcomes

- Docker image creation and container deployment.
- Dockerfile instructions and image versioning.
- Container networking and port mapping.
- Docker volumes and persistent storage.
- Container logs and troubleshooting.
- Running Flask with Gunicorn.

## Future Improvements

- Docker Compose
- Amazon ECR integration
- Jenkins CI/CD pipeline
- Kubernetes deployment
- Container security and optimization

## Author
HARIKRISHNA RAGHU
