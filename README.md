# Docker Compose for WordPress and MySQL containers, for local development

## Build the project
---------------------------------------------------------------------
To run docker-compose in detached mode, pull in the needed Docker images, and starts the wordpress and database containers, run:
```bash
docker-compose up -d
```



## Shutdown and cleanup
---------------------------------------------------------------------
To remove the containers and default network, but preserves your WordPress database, run:
```bash
docker-compose down
```

To remove the containers, default network, and the WordPress database, run:
```bash
docker-compose down --volumes
```
