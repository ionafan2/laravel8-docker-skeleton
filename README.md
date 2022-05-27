## Laravel 8 Docker-compose Skeleton

Repository to clone and starting make something awesome with laravel!

### Laravel version 8.83.14

### Containers:

[See config files here](config/docker/)

#### Docker

* php:8.0.14-fpm
* nginx:stable-alpine
* mysql:5.7.38
* redis:4.0
* mailhog:latest


#### Composer

* "barryvdh/laravel-debugbar": "^3.6",
* "barryvdh/laravel-ide-helper": "^2.12",
* "predis/predis": "^1.1"


### How to use:

- Clone this repository
- In [docker-compose.yml](docker-compose.yml) replace `CHANGEME`
- Rename [Nginx config](config/docker/containers/nginx/conf/projecturl.conf) and replace `CHANGEME`
- Run docker-compose up
- Create or clone .env by .env.example
- Verify if docker has access to files
- Run command: `composer install`

Fix all issues and you will be free! =)
