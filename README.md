# Sonarqube compose

Docker compose file for creating a Sonarqube container and a PostgreSQL database container.

## Prerequisites

- Docker and Docker-Compose
- You may need to [increase the vm.max_map_count kernel setting](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html#docker-prod-prerequisites)

## Running

```bash
docker-compose up
```

When done:

```bash
docker-compose down
```
