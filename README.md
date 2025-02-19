# Docker Setup for Keycloak and PostgeSQL
This is a predefined environment that will run Keycloak and PostgreSQL in their own docker containers. This is meant to be used a starting point for application development with database and authentication support.

## Useful commands
Start both containers in detached mode:
```
docker compose up -d
```

Shutdown both containers:
```
docker compose down
```

Run bash inside a specific container:
```
docker exec -it <container_id_or_name> bash
```
