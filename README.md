# local-infrastructure

To start this , make sure , you have:
- Docker installed
- Docker Compose V2 (Docker latest version comoes with this features)

To start:

```
    docker compose up -d
```

To Stop:

```
 docker compose down

 # To removed the volume 
 docker compose down -v
```

To access the application with Treafik reverse proxy , use this endpoint :
* [grafana.localhost](grafana.localhost) .
* [nginx.localhost](nginx.localhost) .
* [control-center.localhost](control-center.localhost) .