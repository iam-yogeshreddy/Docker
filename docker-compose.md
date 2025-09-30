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

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙪𝙥 : Build, (re)create, start, and attach to containers

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙪𝙥 -𝙙 : Run containers in detached (background) mode

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙙𝙤𝙬𝙣 : Stop and remove containers, networks, and optionally volumes

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙨𝙩𝙤𝙥 : Stop running containers without removing them

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙨𝙩𝙖𝙧𝙩 : Start previously stopped containers

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙧𝙚𝙨𝙩𝙖𝙧𝙩 : Restart running containers

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙥𝙨 : List containers and their status

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙡𝙤𝙜𝙨 : View logs of all containers

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙡𝙤𝙜𝙨 -𝙛 <𝙨𝙚𝙧𝙫𝙞𝙘𝙚_𝙣𝙖𝙢𝙚> : streams real-time logs of a specific service defined in our Compose file

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙘𝙤𝙣𝙛𝙞𝙜 --𝙨𝙚𝙧𝙫𝙞𝙘𝙚𝙨 : List all services defined

docker compose config --volumes : List all volumes defined

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙪𝙥 --𝙨𝙘𝙖𝙡𝙚 <𝙨𝙚𝙧𝙫𝙞𝙘𝙚>=<𝙣𝙪𝙢> : Scale a service to a specific number of instances

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙙𝙤𝙬𝙣 --𝙫𝙤𝙡𝙪𝙢𝙚𝙨 : Remove containers and volumes created by Compose

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙧𝙢 : Remove stopped containers

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙥𝙧𝙪𝙣𝙚 : Clean up unused containers, networks, images, and optionally volumes

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 𝙫𝙚𝙧𝙨𝙞𝙤𝙣 : Show Docker Compose version

𝙙𝙤𝙘𝙠𝙚𝙧 𝙘𝙤𝙢𝙥𝙤𝙨𝙚 --𝙝𝙚𝙡𝙥 : Show full help with commands and flags
