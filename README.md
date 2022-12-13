# E-Commerce-Microservices-App-Deployment

## First Deploy practice for Microservices app which build with many different environments and technologies.

# Clone source code of Emart App

git clone https://github.com/devopshydclub/emartapp.git
ls
cd emartapp/
ls

# Bring up containers from docker-compose file

vim docker-compose.yaml
docker-compose up -d
docker ps
ip addr show

# Go to browser enter http://VMIp:80

# Clean up

docker-compose down
