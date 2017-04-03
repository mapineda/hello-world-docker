# Hello World Docker

Simple app using docker to "get the hang of things".

## Tech Used:

* PHP
* Apache
* Docker
* [DockerHub](https://hub.docker.com/)

## Getting Started:

1. Download Docker for your dev environment, I'm using the Mac OS image.

2. Install Docker

3. Clone repo

4. build docker using the following commands:

```
docker build -t hello-world .
```

5. run docker:
```
docker run -p 80:80 hello-world
```

6. Add a Volume
```
docker run -p 80:80 -v /Users/mapineda/desktop/coding/docker/hello-world-docker/src:/var/www/html hello-world
```

## Contact:

Email: marco@marcopineda.com

Twitter: @marcoapineda13
