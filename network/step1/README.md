# Networking
---

In this simple example we demonstrate how networking works in docker compose: by default, a network is created for your application with the name of the directory, in this case: `step1_deafult`.
Each container gets an IP in this network, and is reachable by it's name.

In this example, we have a `docker-compose.yaml` in which we have 3 services: We have the `web` which uses the `redit`, and the `client` which we use to communicate with the `web` container. 

## Usage
Run this with `docker-compose up`, then attach to the `client` container, and run:
```
$ curl web:5000
```


