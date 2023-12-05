# Docker image for NodeJS and Libvips

Docker image built from Debian 11(bullseye) and 12(bookworm).

Docker Hub: [link](https://hub.docker.com/repository/docker/frontshop/node-libvips/)


## Usage

Run directly from command:

```docker run --rm -it frontshop/node-libvips -v $(pwd):/app/ /bin/bash -c 'node /app/main.js'  ```

