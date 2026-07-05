# Common Docker Commands

## Overview

This document lists common Docker and Docker Compose commands used in my home lab. These commands help manage containers, review logs, restart services, and troubleshoot self-hosted applications.

## Docker Compose Commands

### Start services

```bash
docker compose up -d
```

Starts the services defined in a `docker-compose.yml` file in the background.

### Stop services

```bash
docker compose down
```

Stops and removes the running containers for the current Compose project.

### Restart services

```bash
docker compose restart
```

Restarts the services defined in the Compose file.

### View running containers

```bash
docker ps
```

Shows currently running containers.

### View all containers

```bash
docker ps -a
```

Shows all containers, including stopped containers.

### View logs

```bash
docker compose logs
```

Shows logs for services in the current Compose project.

### Follow logs live

```bash
docker compose logs -f
```

Streams logs in real time.

### Pull updated images

```bash
docker compose pull
```

Downloads the latest available images for services in the Compose file.

### Recreate containers after updates

```bash
docker compose up -d
```

Recreates containers using the latest pulled images.

## Useful Docker Commands

### Check Docker version

```bash
docker --version
```

Shows the installed Docker version.

### List Docker images

```bash
docker images
```

Shows downloaded Docker images.

### Remove unused Docker resources

```bash
docker system prune
```

Removes unused containers, networks, images, and build cache.

## Security Notes

Before running or publishing Docker commands and configuration files, I should review for:

* Passwords
* API keys
* Tokens
* Private IP addresses
* Internal URLs
* Personal file paths
* Sensitive environment variables

Public examples should use placeholder values and avoid exposing real lab details.

## What I Learned

* How to start and stop Docker Compose services
* How to review running containers
* How to check logs for troubleshooting
* How to update container images
* Why configuration files should be reviewed before being committed to GitHub
