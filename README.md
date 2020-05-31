## Docker Important commands
- docker run <image-name> <command to run on initialization> (Run container in foreground with a command in it)
- docker run -d <image-name> (Run container in detact means in background)
- docker attach <conatiner-id> (To re attach detach container)
- docker ps (List all running containers)
- docker ps -a (List all containers)
- docker stop <container-id> (Stop a running container)
- docker exec <container-id> <command> (Run a command on a running container)
- docker rm <container-id> (Remove container from ps -a listing)
- docker images
- docker rmi <container-id> (Remove images from docker host)
- docker run --name <container-name> <image-name:tag> (Run a container with a name)
- docker run -p 80:5000 <image-name:tag> (Run a container with port mapping from 80 to container port on 5000)
- docker build <docker-file> -t <name:tag> (Build a docker image with a docker file and set it to image name with tag)
- docker network ls (List all Networks)
- docker inspect <container-id> (Inspect gives all json output)
- docker run --name <container-name> --network=none/bridge/host <image-name> (Run a container on network 'none' with image image name)
- docker network create --driver bridge --subnet 182.18.0.1/24 --gateway 182.18.0.1 wp-mysql-network (Create a custom network on driver bridge/none/host with subnet,gateway and network name 'wp-mysql-network')
 
