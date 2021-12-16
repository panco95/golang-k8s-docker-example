### Golang docker&k8s example

Docker Shell:

```shell
docker run -it -p 8080:8080 -v /app/logs:/app/logs panco95/ginecho:v1
```

Docker build:

```
docker build -t panco95/ginecho:v1 .
```

Docker-Compose:

```shell
docker-compose up
```

K8s Deployment(pods):

```shell
kubectl apply -f pod.yml
```

K8s Service:

```shell
kubectl apply -f service.yml
```
