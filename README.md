# API Restful 

[![Rails](https://img.shields.io/badge/Rails->=_7.0.2-gray?style=flat&labelColor=red)](https://img.shields.io/badge/Containers-Docker-blue)
[![Docker](https://img.shields.io/badge/Docker-blue?style=flat&logo=docker)](https://www.docker.com/) 
[![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat&logo=postgresql&logoColor=white)]()
[![](https://img.shields.io/badge/state-on_development-brightgreen)]()

## Description
It's a on development Ruby on Rails APi to serve as backend a E-Commerce app.

This app also use conteiners with Docker and Docker-compose.

This is for part of my personal portfolio.

## Future Feactures 
- [ ] CRUD
- [ ] Purchase system
- [ ] Action Mailer
- [ ] Token Authentication

⚠️ It may have others feactures in future.

## Build in:

| Stack | Version |
| ----- | ------- |
| Ruby  | 2.7.2 |
| Rails | >= 7.0.2.2 |
| Postgres | Lastest |

⚠️ It may have others stacks in future.

## Getting Started
Firstly, there will be 2 branchs! One for everyone to start the project from the beginning and the other for contribution or to see my app in development.

### Installing
#### Prerequisites
>Before installing, you will need Docker in your system. <br>
>You can download and install Docker from here and you can follow the instructions and read the Docker Documentation from here.

#### Commands 
```bash
# Cloning the repository
$ git clone https://github.com/anderson-monte/apirestful.git
$ cd apirestful

# Initializing Docker-compose 
# This will create containers and their images.
$ docker-compose up -d

# Now the server is up, type in your browser http://localhost:3000/.
```
---
To see containers up, type on your preference prompt:
```bash
$ docker ps
```
You will see something like this:
```bash
CONTAINER ID   IMAGE            COMMAND                  CREATED        STATUS             PORTS                    NAMES
df1b3713b318   apirestful_api   "entrypoint.sh bash …"   16 hours ago   Up About an hour   0.0.0.0:3000->3000/tcp   api
46702e618470   postgres         "docker-entrypoint.s…"   16 hours ago   Up About an hour   0.0.0.0:5454->5432/tcp   pg
```
> If you know how to use docker, you can make changes in docker-compose.yml, but I don't recomend to make changes in DockerFile.
