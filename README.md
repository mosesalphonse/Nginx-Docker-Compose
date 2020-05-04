# Nginx-Docker-Compose

Background:

It is a simple Nginx deployment using docker image using Docker Compose.

Manual installation on either local machine or VM usually a tedious process, but docker makes it very simple.

Note: You may use nginx for different other purpose including Load balancer, reverse proxy or just as proxy, terminate SSl etc.

Steps to configure and verify:

git clone https://github.com/mosesalphonse/Nginx-Docker-Compose.git

cd Nginx-Docker-Compose

docker-compose up -d

verify:
curl http://localhost:8000