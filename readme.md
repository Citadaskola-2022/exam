Start containers
```shell
docker compose up -d --build
```

Create vendors folder/install dependencies
```shell
docker compose exec app composer install
```

See currently running containers and ports
```shell
docker ps -a
```