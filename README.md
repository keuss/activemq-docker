# activemq-docker

[Apache ActiveMQ](https://activemq.apache.org/) with [Docker image](https://hub.docker.com/r/rmohr/activemq/)

## Run

 - `docker-compose up -d` (-d option to put it into detach mode)
 - See containers with `docker-compose ps`
 - See volumes with `docker volume ls`
 - Introspect with `docker container inspect myactivemq`
 - Logs `docker-compose logs -f`
 - Stop with `docker-compose down`
 - list all containers : `docker container list -a`, all images : `docker image ls`

## Test

 - ActiveMQ administrative [interface](http://127.0.0.1:8161/admin/) (admin/admin)
