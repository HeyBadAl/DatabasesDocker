# Docker Compose for Databases

This repository contains Docker Compose configurations for running various databases and their web interfaces using Docker.

## Overview

The following services are inclued:

- MySQL
- Adminer (Database management tool)
- PostgreSQL
- MongoDB
- Mongo Express (Web-based MongoDB admin interface)
- Redis
- Redis Commander (Redis management tool)

## Usage

#### Prerequisites

- Docker

#### Running services

```bash
docker compose up -d
```

**To run individual services, navigate to their respective directories and run `docker-compose up -d.`**

#### Accessing Web Interfaces

- Adminer: http://localhost:8080
- Mongo Express: http://localhost:8081
- Redis Commander: http://localhost:8082

#### Stopping Services

To stop all services:

```bash
docker compose down
```

## Configuration

Each service has its own `docker-compose.yml` file in its respective directory. You can customize settings such as volumes, ports, environment variables, etc., as needed.
