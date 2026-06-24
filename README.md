# Dockerized Two-Tier Flask Application

This repository contains my Docker Compose setup for running a two-tier Flask and MySQL application using Docker containers.

## My Contribution

* Created and configured `docker-compose.yml`
* Configured MySQL and Flask services
* Added Docker networking and volumes
* Added container health checks
* Deployed and tested on AWS EC2

## Tech Stack

* Docker
* Docker Compose
* Flask
* MySQL
* AWS EC2

## Run the Application

```bash
docker compose up -d
```

## Verify Containers

```bash
docker ps
```

The Flask application will be available on:

```text
http://<EC2-Public-IP>:5000
```

## Note

The original Flask application code belongs to the original project author ( Londhe Shubham ). This repository focuses on my Docker Compose configuration and deployment work.
