# full-server-docker-setup
A docker setup for my personal server running multiple apps using docker-compose and docker-secrets
These files are heavily inspired from [William Patton's blog post](https://www.pattonwebz.com/docker/multiple-wordpress-containers-proxy/)

# Getting Started
Create a docker network for the containers to speak to each other by running:
```sh
$ docker network create nginx-proxy
```
