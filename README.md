# laravel7-dockerize

# Usage : 

First, you need to build it, follow this command :
docker-compose build

Second, you run the container, command :
docker-compose up -d

Configuring .env files :
DB_HOST=mysql
APP_URL=http://localhost:8080

Access The App :
http://localhost:8080

Exec Command :
The command : docker-compose exec {container_name} /bin/sh
example for migration : docker-compose exec php php /var/www/artisan migrate


Start / Stop Container :
to stop : docker-compose stop
to start : docker-compose start

Destroy Container :
docker-compose down




