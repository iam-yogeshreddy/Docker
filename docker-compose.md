𝐃𝐨𝐜𝐤𝐞𝐫 𝐂𝐨𝐦𝐩𝐨𝐬𝐞 :

Docker Compose is a tool for 𝐝𝐞𝐟𝐢𝐧𝐢𝐧𝐠, 𝐫𝐮𝐧𝐧𝐢𝐧𝐠, 𝐚𝐧𝐝 𝐦𝐚𝐧𝐚𝐠𝐢𝐧𝐠 𝐦𝐮𝐥𝐭𝐢-𝐜𝐨𝐧𝐭𝐚𝐢𝐧𝐞𝐫 𝐃𝐨𝐜𝐤𝐞𝐫 𝐚𝐩𝐩𝐥𝐢𝐜𝐚𝐭𝐢𝐨𝐧𝐬 using a single configuration file (docker-compose.yml). Instead of manually starting each container with docker run, Compose lets you orchestrate multiple services, networks, and volumes together.



𝐊𝐞𝐲 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬 :


1. 𝐔𝐧𝐢𝐟𝐢𝐞𝐝 𝐂𝐋𝐈 :
docker compose is part of the Docker CLI. No separate binary is needed. 


2. 𝐌𝐮𝐥𝐭𝐢-𝐜𝐨𝐧𝐭𝐚𝐢𝐧𝐞𝐫 𝐨𝐫𝐜𝐡𝐞𝐬𝐭𝐫𝐚𝐭𝐢𝐨𝐧 :
-> Start multiple containers (web server, database, cache, etc.) at once.

-> Services can communicate by name, and dependencies can be defined.


3. 𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐝 𝐛𝐮𝐢𝐥𝐝𝐬 :
Support for multi-architecture images, build-time secrets, SSH forwarding, and caching.


4. 𝐁𝐞𝐭𝐭𝐞𝐫 𝐯𝐨𝐥𝐮𝐦𝐞 & 𝐧𝐞𝐭𝐰𝐨𝐫𝐤 𝐦𝐚𝐧𝐚𝐠𝐞𝐦𝐞𝐧𝐭 :
Lifecycle of resources is handled predictably and efficiently.


5. 𝐂𝐥𝐨𝐮𝐝-𝐧𝐚𝐭𝐢𝐯𝐞 :

Enables deployment, scaling, and management of multi-container applications seamlessly in local, cloud, or on-premises environments using OCI standards.


𝐂𝐨𝐦𝐦𝐚𝐧𝐝𝐬 :


docker compose up : Build, (re)create, start, and attach to containers

docker compose up -d : Run containers in detached (background) mode

docker compose down : Stop and remove containers, networks, and optionally volumes

docker compose stop : Stop running containers without removing them

docker compose start : Start previously stopped containers

docker compose restart : Restart running containers

docker compose ps : List containers and their status

docker compose logs : View logs of all containers

docker compose logs -f <service-name> : streams real-time logs of a specific service defined in our Compose file

docker compose config --services : List all services defined

docker compose config --volumes : List all volumes defined

docker compose up --scale <service>=<num> : Scale a service to a specific number of instances

docker compose down --volumes : Remove containers and volumes created by Compose

docker compose rm : Remove stopped containers

docker compose prune : Clean up unused containers, networks, images, and optionally volumes

docker compose version : Show Docker Compose version

docker compose --help : Show full help with commands and flags
