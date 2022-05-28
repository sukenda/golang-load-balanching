# golang-load-balancing

### [Source](https://codeburst.io/load-balancing-go-api-with-docker-nginx-digital-ocean-d7f05f7c9b31)

### Build docker file
```shell
docker build -t golang-load-balancing-api .
```

### Show build image
```shell
docker images
```

### Docker delete image
```shell
docker image rm -f <IMAGE ID>
```

### Run a container
```shell
docker run --name api --rm -p 3000:3000 golang-load-balancing-api
```

### Run Docker Compose
```shell
docker-compose up --build
```

### Removed Docker Compose
```shell
docker-compose down
```

### Run docker compose using load balancing
```shell
docker-compose --compatibility up --build
```