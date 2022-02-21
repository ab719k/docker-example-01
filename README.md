# docker-example-01

docker commands to build the example and push it to a public repository. The example code comes from the docker compose page[^1]

```
$ docker container commit 66183d81925d amitbhatia76/rpi4_hello_world:tagname
$ docker build -t amitbhatia76/rpi4_hello_world . 
$ docker run amitbhatia76/rpi4_hello_world
$ docker login
$ docker push amitbhatia76/rpi4_hello_world
$ docker ps
```


To start docker use either of the following commands
```bash
$ docker-compose up
# Background
$ docker-compose up -d
```
To stop the
```bash
$ docker-compose stop
$ docker-compose down
# You can bring everything down, removing the containers entirely, with the down command. Pass --volumes to also remove the data volume used by the Redis container
$ docker-compose down --volumes
```

[^1]: [Docker Compose Getting Started](https://docs.docker.com/compose/gettingstarted/)

