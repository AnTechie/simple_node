# simple_node
docker build . will run the Dockerfile to create an image
docker images will print all the available images
docker run {IMAGE_ID} will run a container with the image
docker ps will print all the running containers
docker kill {CONTAINER_ID} will terminate the container
# to access the deployed image locally,bind the container port to the local port using below command
docker run -p 8080(port from container):8080 container(ex:User:latest) 
