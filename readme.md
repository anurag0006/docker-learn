**Starting docker locally**
systemctl start docker

**Lists all the running containers**
docker ps

**List of all the images that we have in our system**
docker image ls

**To stop the container**
docker stop container-name(or id)

**list of all the volumes**
docker volume ls

**Logs of all the container**
docker logs container-name

**Delete all the stopped containers**
docker container prune

**Lists all the networks available**
docker network ls

**Creating a required network which can be used for inter container communications**
docker network create xyz

**Getting Containers Up**
docker-compose -f docker-compose.yaml up

**Getting Containers Down**
docker-compose -f docker-compose.yaml down
