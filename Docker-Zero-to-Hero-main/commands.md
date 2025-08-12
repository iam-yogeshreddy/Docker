# Docker Commands

Some of the most commonly used docker commands are 

### docker images

Lists docker images on the host machine.

### docker build

Builds image from Dockerfile.

### docker run

Runs a Docker container. 

There are many arguments which you can pass to this command for example,

`docker run -d` -> Run container in background and print container ID
`docker run -p` -> Port mapping

use `docker run --help` to look into more arguments.

### docker ps

Lists running containers on the host machine.

### docker stop

Stops running container.

### docker start

Starts a stopped container.

### docker rm 

Removes a stopped container.

### docker rmi

Removes an image from the host machine.

### docker pull

Downloads an image from the configured registry.

### docker push

Uploads an image to the configured registry.

### docker exec

Run a command in a running container.

### 𝐝𝐨𝐜𝐤𝐞𝐫 𝐩𝐬 -𝐚

Lists all containers — running, stopped, exited, or just created

### docker ps -a -f status=exited

To list stopped Docker containers

### 𝐝𝐨𝐜𝐤𝐞𝐫 𝐢𝐦𝐚𝐠𝐞 𝐩𝐫𝐮𝐧𝐞

Removes all dangling images — images that have no tag (<none>) and aren’t used by any container

### 𝐝𝐨𝐜𝐤𝐞𝐫 𝐜𝐨𝐧𝐭𝐚𝐢𝐧𝐞𝐫 𝐩𝐫𝐮𝐧𝐞 

Remove all stopped containers

### 𝐝𝐨𝐜𝐤𝐞𝐫 𝐥𝐨𝐠𝐬 𝐂𝐎𝐍𝐓𝐀𝐈𝐍𝐄𝐑_𝐈𝐃 

View container logs
