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

[^1]: [Docker Compose Getting Started](https://docs.docker.com/compose/gettingstarted/)

