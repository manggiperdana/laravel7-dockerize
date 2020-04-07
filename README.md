# laravel7-dockerize

# Usage : 

First, you need to build it, follow this command :
docker-compose build
<br/><br/>
Second, you run the container, command :
docker-compose up -d
<br/><br/>
Configuring .env files :
DB_HOST=mysql
APP_URL=http://localhost:8080
<br/><br/>
Access The App :
http://localhost:8080
<br/><br/>
Exec Command :
The command : docker-compose exec {container_name} /bin/sh <br/>
example for migration : docker-compose exec php php /var/www/artisan migrate
<br/><br/>
Start / Stop Container :
to stop : docker-compose stop
to start : docker-compose start
<br/><br/>
Destroy Container :
docker-compose down




