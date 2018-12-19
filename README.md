# Stores App - Main Repository
This repository contains de Docker-Compose file to mount the stores app (frontend, backend and database) in docker.

## Steps
1. Install docker (https://docs.docker.com/install/#pre-releases)
1. Install docker-compose (https://docs.docker.com/compose/install/)
1. Clone this repository with its submodules `git clone --recurse-submodules git@github.com:dasetova/stores_deploy.git`
1. In the main repository (this one) run `sudo docker-compose up -d`
1. Visit http://localhost/ to see frontend or http://0.0.0.0:4000/api/stores/ to test de backend (refer to doc folder in backend repository to see postman collection).
