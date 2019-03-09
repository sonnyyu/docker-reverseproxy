docker-compose up --build

docker-compose up -d

docker-compose stop

docker-compose down

docker container prune -f

docker image prune -a -f

docker volume prune -f

docker network prune -f

docker system prune -f

sudo rm -rf /var/lib/docker/volumes/*

docker exec -it  docker-nginx /bin/sh

/var/log/nginx/host.access.log

docker exec -it   docker-apache /bin/sh

/usr/local/apache2/logs/access_log
