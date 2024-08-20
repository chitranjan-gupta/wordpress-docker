# wordpress-docker
### This is creates a docker container containing wordpress and apache2 server.

## Requirements
> Add all the environment variable otherwise it will show Error Connecting with the database

## Build
```sh
docker build -t my-wordpress
```

## Run
```sh
docker run -p 8000:80 -d --env-file .env my-wordpress
```

## Stop
```sh
docker stop <container_id>
```

## Start
```sh
docker start <container_id>
```

## logs
```sh
docker logs <container_id>
```