### create and running a container 
- `docker run <imagename> `
- `docker run hello-world` 
- `docker create <image-name>`
- `docker start <container-id>`


### Overriding default commands
- `docker run <imagename> <cmd>`
- `docker run busybox echo hi there`
- `docker run busybox echo ls`

### Listing cotainers
- `docker ps`

### docker watch 
- `docker start -a <container-id>`
- `a -` flag to watch the container

### remove the stopped container
- `docker system prune`

### retreiveing the logs
-` docker logs <container-id>`

### stopping containers
- `docker kill or stop `

### Multi-command container
- `docker exec -it <containerid> cmd`
- i attach the stdin terminal of the process
- t pretty output 

### get a shell access - full terminal access
- docker exec -it <id> `sh`
- get access to unix env

###  remove the container when it exits
- ` docker run -i -t --rm=true centos /bin/bash`
