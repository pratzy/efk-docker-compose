```shell
docker-compose up -d

docker pull nginx:alpine
docker run --name nginx_container -d --log-driver=fluentd -p 8080:80 nginx:alpine

```

```shell
curl localhost:8080
```
