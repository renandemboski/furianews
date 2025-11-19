## Docker Command Explanation

## Docker Compose

> **`docker compose up`**  
> Reads the `docker-compose.yml` file and starts all services at once, creating and running the necessary containers, networks, and volumes.

> **`docker compose up -d`**  
> Starts all services in detached mode (runs in the background).

> **`docker compose down`**  
> Stops and removes all services, networks, and resources created by Compose.

> **`docker compose build`**  
> Builds or rebuilds images defined in the compose file.

> **`docker compose stop`**  
> Stops all running services defined in the compose file.

> **`docker compose start`**  
> Starts previously stopped services without recreating them.

> **`docker compose up -d --force-recreate`**  
> Starts all services in detached mode and forces every container to be recreated, even if nothing changed, ensuring a clean and fresh build of the environment.

---

> **`docker --version`**  
> Shows the installed Docker version.

> **`docker ps`**  
> Lists all running containers.

> **`docker ps -a`**  
> Lists all containers, including stopped ones.

> **`docker images`**  
> Shows all images stored locally.

> **`docker pull <image>`**  
> Downloads an image from Docker Hub.

> **`docker run <image>`**  
> Creates and starts a new container from that image.

> **`docker stop <container>`**  
> Stops a running container.

> **`docker start <container>`**  
> Starts a stopped container.

> **`docker restart <container>`**  
> Restarts a container.

> **`docker rm <container>`**  
> Removes a container.

> **`docker rmi <image>`**  
> Removes an image.

> **`docker logs <container>`**  
> Shows a container’s logs.

> **`docker exec -it <container> bash`**  
> Opens an interactive shell inside the container.

> **`docker build -t <name> .`**  
> Builds an image from the Dockerfile in the current folder.

> **`docker network ls`**  
> Lists all Docker networks.

> **`docker volume ls`**  
> Lists all Docker volumes.
