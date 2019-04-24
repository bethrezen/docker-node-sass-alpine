# Description
Dockerfile which installs Node-SASS in an Alpine Linux image.

# Docker Hub
https://hub.docker.com/r/bethrezen/node-sass-alpine/

# Pull image
docker pull bethrezen/node-sass-alpine

# Run image
docker run bethrezen/node-sass-alpine:<NODE_VERSION> node-sass-alpine

# Upgrade Node

* `docker build -t bethrezen/node-sass-alpine:latest .`
* `docker push bethrezen/node-sass-alpine:latest`
