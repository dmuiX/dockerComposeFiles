# my DockerCompose repo
## Description

This Repository contains my docker-compose files that I use on my home server.

## Disclaimer
The State of these files is as it is. Might contain some errors or inconsistencies. And I have deleted all passwords from the env files. Might change some of them to docker secrets in the future.

## Specialities

1. pihole is configured to use an ip-address from the host network 192.168.1.1/24
2. swag is providing lets encrypt certificates and subdomain configs on virtual-lab.pro
3. dockerproxy is providing configurable limited access to the docker socket, which are used by watchtower, portainer and code-server
4. portainer is providing a nice gui to see whats going on - basically my omv is doing it very similiar
5. watchtower is updating every container automatically daily that has the label "com.centurylinklabs.watchtower.enable=true"

## Swag
I have written an article about how to setup let's encrypt certificates on a private network with swag on medium:
https://dmuix.medium.com/working-swag-docker-compose-config-for-local-network-7f9734858432