# docker1
Setup Nginx, Jenkins and Nexus by Docker Compose with options:
1. Nginx redirect to Jenkins and Nexus
2. Jenkins store all jobs and configuration data in external volume
3. Nexus store all artifacts in external volume
4. Restrict Jenkins to use no more than 500MB RAM
5. Restrict Jenkins to utilize no more than 35% CPU
6. Restrict Nexus to utilize no more than 25% CPU
7. Send logs to journald
8. Custom network and IP addresses

Also incluide:
1. swarm.yml for Docker Swarm, which setup Nginx, Jenkins and Nexus with same options (except custom network and IP addresses)
