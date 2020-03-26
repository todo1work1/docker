# docker
My Docker Learnings
- docker -v
- ``` docker container run <image-name> <app-name> ```

    eg. docker container run alpine:3.4 uptime
- Image Format
  - registry/namespace/repository:tag
  - eg. ``` registry.docker.io/user/ubuntu:latest ```
- Launch Container events
  - Image Pull
  - Container Create
  - Container Attach
  - Network Create
  - Container Start
  - Container Die
  - Network Disconnect
- Docker Container Status ``` docker container ps ```
- Docker run **interactive Mode** ```docker container run -i -t  <image-name:tag-name> <app-name>``` -t=> allocate tty
- Docker Container List ``` docker container ps -l ``` ``` docker container ps -n 2``` ``` docker container ps -a ```
- Docker Container persist ``` docker container -idt <image-name> <app-name> ``` idt=> detach
- Docker Container Logs ``` docker container ps ``` ``` docker container logs <container id/name> ``` ``` docker container logs -f <container id/name> ``` 
- Docker Run Commands ``` docker container ps ``` ``` docker container exec <container-id> <command> ``` ``` docker container exec -it <container-id> <command> ```
- Docker Container Pause ``` docker container pause <container-id> ```
- Docker Container UnPause ``` docker container unpause <container-id> ```
- Docker Disk Usage ``` docker system df ```
- Docker Container stop ``` docker container stop <container-id> ```
- Docker Container destroy ``` docker container rm <container-id> ```
