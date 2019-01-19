# docker run 

## Create apline image with htop
```
docker build -t myhtop --file ./DockerfilePID .
```
## Sharing Hosts PID namespace
```
docker run -it --rm --pid=host myhtop bash
```