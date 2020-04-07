# laravel7-dockerize

# Usage : 

First, you need to build it, follow this command :<br/>
docker-compose build
<br/><br/>
Second, you run the container, command :<br/>
docker-compose up -d
<br/><br/>
Configuring .env files :<br/>
DB_HOST=mysql<br/>
APP_URL=http://localhost:8080<br/>
<br/><br/>
Access The App :<br/>
http://localhost:8080
<br/><br/>
Exec Command :<br/>
The command : docker-compose exec {container_name} /bin/sh <br/>
Example for migration : docker-compose exec php php /var/www/artisan migrate
<br/><br/>
Start / Stop Container :
<br/>
to stop : docker-compose stop
<br/>
to start : docker-compose start
<br/><br/>
Destroy Container :<br/>
docker-compose down




