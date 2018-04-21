# PHP Nginx Docker
This project is a very simple example of how to set up a PHP + Nginx application
with Docker.

It is largely inspired from 
http://geekyplatypus.com/dockerise-your-php-application-with-nginx-and-php7-fpm/

# Installation
`git clone https://gitlab.com/docker-webapp/php-nginx-docker.git`

# Run
```
cd php-nginx-docker
docker-compose up
```

# Run in background
```
cd php-nginx-docker
docker-compose up -d
```

Once launched, the application is available at [localhost:80](localhost:80)

# Stop the application running in background
`docker-compose down`
