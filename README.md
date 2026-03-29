# Commands used for Installation of Docker in Linux RHEL:

* sudo dnf -y install dnf-plugins-core
* sudo dnf config-manager --add-repo https://download.docker.com/linux/rhel/docker-ce.repo
* sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y
* sudo systemctl start docker
* sudo systemctl enable docker
* sudo usermod -aG docker ec2-user

## Enable & Status Checking

* sudo systemctl enable docker
* sudo systemctl status docker

# Docker Commands

## Basic Commands:

docker --version			-> Check version
docker version				-> Detailed version information
docker info				-> System information
docker help				-> List all commands

## Container Commands:

docker ps 				-> Running containers
docker ps -a				-> All the containers
docker create nginx 			-> Creates the containers, status is created
docker start <container-id> 		-> Start the container
docker stop <container-id>		-> Stop the container
docker rm <container-id> 		-> Remove the container
docker run nginx 			-> pull + create + start

## Image Commands:

docker images 				-> Available Images
docker pull nginx 			-> Pull the image from dockerhub (download)
docker rmi nginx 			-> Remove the image
