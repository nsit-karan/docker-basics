# docker-basics

# common docker commands
* docker info (gives relevant info about docker - ram, etc)
* docker pull python (pull images from dockerhub)
* docker images (all the images present on the system)
* docker build -i my_image . (. implies that the dockerfile is present in the current dir)
* docker run --name node_app -p 3000:3000 -d nodejs
