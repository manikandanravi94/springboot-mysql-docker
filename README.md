# springboot-docker
sample for spring-boot docker implementation
Docker sample application

Docker sample commands:

Docker file commands:

1. From --> to pull the image from docker hub
2. Add  --> copy the jar from target folder from app to docker root path of the container
3. Expose --> expose a port on which the app will be exposed from docker
4. Entrypoint --> it is used to run the app when the container is started

Docker CLI commands:

1. docker build -f Dockerfile -t <image name> .(. represent the current folder)
2. docker images    [once built docker image will be created.. to list down the images..]
3. docker run -p 8086:8086 -d image-name --> -p is the port where the port is mapped with local to the docker port -d run the container in detached mode
4. docker containter ls --> list the containers
5. docker stop containerid --> vl stop the running container
6. docker logs -f conatinerid --> vl see the container logs which are running in the detached mode
7. history --> vl list the docker command history which we used so far

