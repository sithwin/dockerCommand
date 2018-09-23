# dockerCommand
======= Machine ========
// Machine
docker-machine ls => to view VM name
docker-machine start [machine name]
docker-machine stop [machine name]

// Environment
docker-machine evn [machine name]   
eval "$('C:\Program Files\Docker Toolbox\docker-machine.exe' env default)"

// Machine IP Address
docker-machine ip [machine name]

// Machine Status
docker-machine status [machine name]

===== Client =========
docker pull [image name]
docker pull hello-world

docker run [image name]
docker run hello-world
docker run -p 80:80 kitematic/hell0-world-nginx=
docker stop [container id]

docker images 

// List all the containers
docker ps -a

// Remove Container
docker rm [container id]

// Remove Images
docker rmi [Image Id]

Docker Volume
=============
Can be shared and reused among containers


