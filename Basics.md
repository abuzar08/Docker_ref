# Docker Basics
#### Get info
`docker info`

#### List everything
`docker ps`

 or  

 `docker ps -a`   

 This will show non running images too

#### Run a container

 `docker container run -d -p 8080:80 --name myname <image>`

#### Delete

 `rm` = remove

`docker container rm <name>`

`docker rm $(docker ps -aq) -f`  The -f here is to force quit running containers.

#### Stop

`docker stop <name>`
