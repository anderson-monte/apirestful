# API Restful 

[![Rails](https://img.shields.io/badge/Rails->=_7.0.2-gray?style=flat&labelColor=red)](https://rubyonrails.org/)
[![Docker](https://img.shields.io/badge/Docker-blue?style=flat&logo=docker)](https://www.docker.com/) 
[![Postgres](https://img.shields.io/badge/Postgres-4169E1?style=flat&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![](https://img.shields.io/badge/state-on_development-brightgreen)]()

## Description
It's a on development Ruby on Rails APi to serve as backend a E-Commerce app.
containers
This app also use  with Docker and Docker-compose.

This is for part of my personal portfolio.

## Future Features 
- [ ] CRUD
- [ ] Purchase system
- [ ] Action Mailer
- [ ] Token Authentication

>⚠️ It may have others features in future.

## Build in:

| Stack | Version |
| ----- | ------- |
| Ruby  | 3.1.1 |
| Rails | >= 7.0.2.2 |
| Postgres | Latest |

>⚠️ It may have others stacks in future.

## Getting Started
Firstly, there will be 2 branchs! One for everyone to start the project from the beginning and the other for contribution or to see my app in development.

### Installing
#### Prerequisites
>Before installing, you will need Docker in your system. <br>
>You can download Docker and follow instructions and read the Docker Documentation from [here](https://docs.docker.com/).

#### Commands 
```bash
# Cloning the repository
$ git clone https://github.com/anderson-monte/apirestful.git
$ cd apirestful

# Initializing Docker-compose 
# This will create containers and their images.
$ docker-compose up -d --build

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
> If you know how to use docker, you can make changes in docker-compose.yml, but I don't recommend to make changes in DockerFile.
