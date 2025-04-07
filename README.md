# Node.js CI/CD with GitHub Actions and Docker

This repository demonstrates a CI/CD pipeline for a Node.js app using:
- GitHub Actions for automation
- Docker for containerization
- Docker Hub for image publishing

## CI/CD Steps
1. On every push to `main`, GitHub Actions:
   - Builds the Docker image
   - Pushes it to Docker Hub (shubhranshuranasingh/node-todo-cicd:latest)

## DockerHub
[https://hub.docker.com/r/shubhranshuranasingh/node-todo-cicd](https://hub.docker.com/r/shubhranshuranasingh/node-todo-cicd)
