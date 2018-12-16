# laverna for docker
[![Docker Build Status](https://img.shields.io/docker/build/manzari/laverna.svg)](https://hub.docker.com/r/manzari/laverna/builds)  [![Size](https://img.shields.io/microbadger/image-size/manzari/laverna.svg)](https://hub.docker.com/r/manzari/laverna) 
[![Layers](https://img.shields.io/microbadger/layers/manzari/laverna.svg)](https://hub.docker.com/r/manzari/laverna) 
[![Docker Pulls](https://img.shields.io/docker/pulls/manzari/laverna.svg)](https://hub.docker.com/r/manzari/laverna)

- based on [_/nginx](https://hub.docker.com/_/nginx/)

## Usage
```bash
docker run --name laverna -v ~/laverna_logs:/var/log/nginx:rw -d manzari/laverna
```

