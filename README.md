# project-dockerfiles

To pull the source code of the project
```sh
./update-sourcecode.sh
```

To build the docker image
```sh
docker-compose build
```

To run the all docker containers
```sh
docker-compose up
```

To run in an interactive bash mode in a running docker container
```sh
docker exec -it <container-name> /bin/bash
```

To stop or remove all docker containers
```sh
docker-compose down
```
