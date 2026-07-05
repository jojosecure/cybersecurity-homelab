# Docker Basics

## Overview

Docker is used in my home lab to run self-hosted applications in containers. Containers make it easier to deploy, manage, update, and organize services without installing every application directly on the host system.

## Why I Use Docker

Docker helps make the lab more repeatable and easier to manage. Instead of manually installing each application, I can define how a service should run using Docker commands or Docker Compose files.

## Key Concepts

### Container

A container is a lightweight, isolated environment that runs an application and its dependencies.

### Image

An image is the template used to create a container. It includes the application and the files needed to run it.

### Docker Compose

Docker Compose is used to define and manage multi-container applications using a YAML file.

### Volume

A volume is used to store persistent data so that information is not lost when a container is restarted or recreated.

### Network

Docker networks allow containers to communicate with each other and with the host system when needed.

## Security Considerations

* Avoid storing passwords, tokens, or API keys directly in Docker Compose files
* Use `.env` files for local secrets and exclude them from GitHub
* Review Docker images before using them
* Avoid exposing unnecessary ports
* Keep containers updated
* Use least-privilege access where possible
* Review mounted volumes to avoid exposing sensitive host files
* Do not upload real production or personal configuration values to public repositories

## What I Learned

* How Docker helps organize self-hosted applications
* How containers differ from traditional application installs
* Why persistent volumes are important
* Why exposed ports should be reviewed carefully
* How Docker Compose can make deployments easier to document and repeat

## Future Improvements

* Document commonly used Docker commands
* Add sanitized Docker Compose examples
* Explore container update tools
* Research container vulnerability scanning
* Add backup and restore documentation for container data
