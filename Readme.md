# Docker Commands Reference

## Table of Contents

- [Basic Commands](#basic-commands)
- [Container Management](#container-management)
- [Image Management](#image-management)
- [Network Management](#network-management)
- [Volume Management](#volume-management)
- [Docker Compose](#docker-compose)
- [Utility Commands](#utility-commands)

## Basic Commands

- `docker version`: Display Docker version information.
- `docker info`: Display system-wide information.
- `docker login`: Log in to a Docker registry.
- `docker logout`: Log out from a Docker registry.

## Container Management

- `docker run [OPTIONS] IMAGE [COMMAND] [ARG...]`: Create and start a container.
- `docker ps`: List running containers.
- `docker ps -a`: List all containers.
- `docker stop [CONTAINER_ID]`: Stop one or more running containers.
- `docker start [CONTAINER_ID]`: Start one or more stopped containers.
- `docker restart [CONTAINER_ID]`: Restart one or more containers.
- `docker rm [CONTAINER_ID]`: Remove one or more containers.
- `docker logs [CONTAINER_ID]`: Fetch the logs of a container.
- `docker exec -it [CONTAINER_ID] [COMMAND]`: Execute a command inside a running container.

## Image Management

- `docker images`: List images.
- `docker pull [IMAGE_NAME]`: Pull an image or a repository from a registry.
- `docker push [IMAGE_NAME]`: Push an image or a repository to a registry.
- `docker rmi [IMAGE_NAME]`: Remove one or more images.
- `docker build -t [TAG] .`: Build an image from a Dockerfile.

## Network Management

- `docker network ls`: List networks.
- `docker network create [OPTIONS] [NETWORK]`: Create a network.
- `docker network rm [NETWORK]`: Remove one or more networks.

## Volume Management

- `docker volume ls`: List volumes.
- `docker volume create [VOLUME_NAME]`: Create a volume.
- `docker volume rm [VOLUME_NAME]`: Remove one or more volumes.

## Docker Compose

- `docker-compose up`: Build and start your containers.
- `docker-compose down`: Stop and remove containers, networks, images, and volumes.

## Utility Commands

- `docker inspect [NAME|ID]`: Return low-level information on Docker objects.
- `docker stats`: Display a live stream of container(s) resource usage statistics.
- `docker system prune`: Remove unused data.

