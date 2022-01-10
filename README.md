# eng99_docker

- if you have tty error
- `alias docker = "winpty docker"`

# Commands

- docker pull <images_name>
- docker run <images_name>
- docker build -t <image_name>
- docker images
- docker ps
- docker run -d -p host_port:image_port <image_name>

- ghost image port 2368

## Enter container

- docker exec -it <container_ID> bash

## Commit and Push

- docker commit <id> <path_in_dockerhub>:<version>
- docker push <path_in_dockerhub>:<version>

# cp into docker

- docker cp index.html <container_ID>:<path>
