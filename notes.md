# NOTES

Working notes on docker

# Basic commands for dealing with the Ubuntu 18.04 image

* sudo start docker image: `sudo docker run --detach --name ubuntu ubuntu-bionic:1804`
* list running containers: `sudo docker ps`
* shell access: `docker exec -it ubuntu /bin/bash`
* build ubuntu image: `sudo docker build -f ./Dockerfile-ubuntu-18.04 -t ubuntu-bionic:1804 .`
* to exit shell: `exit`
* to stop ubuntu container: `sudo docker stop ubuntu`