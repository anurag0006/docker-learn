systemctl start docker

docker ps // lists all the running containers
docker image ls // list of all the images that we have in our system

docker stop container-name(or id) // to stop the container

docker volume ls //list of all the volumes

docker logs container-name //logs of all the container

docker container prune //delete all the stopped containers

docker network ls //lists all the networks available

docker network create xyz //creating a required network which can be used for inter container communications

**Getting Containers Up**
docker-compose -f docker-compose.yaml up

**Getting Containers Down**
docker-compose -f docker-compose.yaml down
