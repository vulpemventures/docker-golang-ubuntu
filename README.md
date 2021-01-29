# docker-golang-ubuntu

Base Docker Image with Golang on Ubuntu. This can help for building golang binaries with production distro images.

## Build

Replace <tag> with `golang_version`-`ubuntu_version` eg. `1.15.7-ubuntu20.04`

```bash 
$ docker build -t ghcr.io/vulpemventures/golang:<tag> .
```

## Push to Github Container Registry

```bash
$ docker push ghcr.io/vulpemventures/golang:<tag>
```