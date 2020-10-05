# mariadb-docker

Deploy `MariaDB` and `phpMyAdmin` docker image with `docker-compose`.

##### Run containers:
```shell script
docker-compose up -d
```

##### Remove containers without deleting data(volumes):
```shell script
docker-compose down
```

##### Remove containers with data(volumes):
```shell script
docker-compose down -v
```

## Phpmyadmin URL:
http://SERVER_IP:8082

##### Username: `my_username`
##### Password: `my_password`
