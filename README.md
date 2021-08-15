poc-docker-compose-environment-web-deployment

### Introduction
This proof of concept aims to validate an environment built using docker-compose that meets the following requirements

* Supports different environments
* Deploy web applications configured using environment variables

### Requisites

* Docker

### How to run

* Edit host file adding the entries : web.prod.carloshh.dev, web.test.carloshh.dev
* Build webapp image in image folder using the command `docker build . -t webapp`
* Start the docker-compose files in environment folder
* Check URL: `http://web.test.carloshh.local/`
* Check URL: `http://web.prod.carloshh.local/`
