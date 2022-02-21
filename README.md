# docker-example-01


docker commands to build the example and push it to a public repository

 docker container commit 66183d81925d amitbhatia76/rpi4_hello_world:tagname
 docker build -t amitbhatia76/rpi4_hello_world .
 docker run amitbhatia76/rpi4_hello_world
 docker login
 docker push amitbhatia76/rpi4_hello_world
 docker ps
