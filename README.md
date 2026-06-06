# DevOps Docker Project

This is my first DevOps project built using Python, Flask, Docker, Git, and GitHub.

## Technologies Used
- Python
- Flask
- Docker
- Git
- GitHub

## Features
- Flask web application
- Dockerized deployment
- Containerized execution
- Version control with Git
- Hosted on GitHub

## Project Structure

Devops Project
│── app.py
│── Dockerfile
│── requirements.txt
│── .gitignore
│── README.md

## How to Run

### Build Docker Image

docker build -t my-first-devops-app .

### Run Docker Container

docker run -p 5000:5000 my-first-devops-app

### Open Browser

http://localhost:5000