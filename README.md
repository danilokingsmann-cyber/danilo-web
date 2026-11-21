# Danilo Web

A simple Dockerized web application created during my DevOps practice.

## Run locally

docker build -t danilo-web:v1 .
docker run -d --name danilo-web-container -p 8085:8000 danilo-web:v1

Open http://localhost:8085
