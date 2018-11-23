# laverna for docker
![Docker Build Status](https://img.shields.io/docker/build/manzari/laverna.svg) ![Size](https://img.shields.io/microbadger/image-size/manzari/laverna.svg) ![Layers](https://img.shields.io/microbadger/layers/_/httpd.svg) ![Docker Pulls](https://img.shields.io/docker/pulls/manzari/laverna.svg)

- based on [_/nginx](https://hub.docker.com/_/nginx/)

## Usage
```bash
docker run --name laverna -v ~/laverna_logs:/var/log/nginx:rw -d manzari/laverna
```

