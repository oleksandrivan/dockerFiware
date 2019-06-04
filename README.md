# Docker Compose YAML for Fiware deployment
With this file we are able to deploy all needed Docker infrastructure for our Fiware scenario

# Prerequisites 
We need to install Docker CE and Docker compose following the next [tutorial](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce)

# Run 
To start the infrastructure
```bash
sudo docker-compose -f docker-agent.yml up -d 
```
# Stop
To stop the infrastructure and destroy containers
```bash
sudo docker-compose -f docker-agent.yml down
```
