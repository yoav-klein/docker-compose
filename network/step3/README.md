# Networking - using container_name
---

This example adds on the `step1`. Here we use the `container_name` service-level field.
This has 2 effects:
1. Sets the container name when you run `docker container ls` for example
2. You can also reach the container using this name, in addition to the name of the service.


## Run
```
$ docker-compose up -d
$ docker exec -it client /bin/bash
$ ping web
$ ping webos
```
