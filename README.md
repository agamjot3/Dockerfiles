# Dockerfiles
Basic Examples Of Dockerfiles

//Dockerfile-1
This file is an example to create docker images for backend applications that use NodeJS & ExpressJS.
It creates a docker image that runs the backend application on Port:8083(both internal & external)


// Docker-Compose File (docker-compose.yml)
This file will spin up a docker container based on the image name provided.
This file will also map and expose accordingly as defined.
Command -- sudo docker-compose pull  (Pull The reference image)
        -- sudo docker-compose up -d (Run the reference image as a container in the deamon)
