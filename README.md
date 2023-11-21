# my DockerCompose repo
## Description

This Repository contains my docker-compose files that I use on my home server.

## Specialities

1. pihole is configured to use an ip-address from the host network 192.168.1.1/24
2. swag is providing lets encrypt certificates and subdomain configs on virtual-lab.pro
3. dockerproxy is providing limited access to the docker socket, which are used by watchtower, portainer
4. portainer is providing a nice gui to see whats going on - basically my omv is doing it very similiar
5. watchtower is updating every container automatically daily that has the label ""