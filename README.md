# Introduction to Machine Learning - Docker ![Docker Pulls](https://img.shields.io/docker/pulls/noah95/introml.svg)
Unofficial Docker container to run the ETH Intro to ML demos.

## Pull
If you wish to download the finished built docker image from docker hub, run:
```bash
docker pull noah95/introml
```

## Run
This command starts the docker container:
```bash
docker run -p 8888:8888 -v `pwd`:"/home/jovyan/iml" introml

```
Jupyter is now available at [localhost:8888](localhost:8888)

## Build
```bash
docker built . -t introml
```

## Push
```bash
docker tag introml noah95/introml
docker push noah95/introml
```
