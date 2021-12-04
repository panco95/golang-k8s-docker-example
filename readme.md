### Golang docker image example


Docker-Compose

```shell
docker-compose up
```

**OR**

Docker

```shell
docker run -it -p 8080:8080 -v /app/logs:/app/logs panco95/ginecho:v1
```