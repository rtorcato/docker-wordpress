# wordpress-docker

Use Docker to setup Wordpress, MySQL & PHPMyAdmin

Get Docker Desktop for your system: https://www.docker.com/products/docker-desktop if you don't have it running already.

Git clone this project and run:

```
$ docker-compose up -d
```
## Site
Then visit your site at 

```
http://localhost
```

## Admin
Administration page is located at 
```
http://localhost/admin
```

## PhpMyAdmin
```
http://localhost:8080
```
Username: Root Password: p4ssw0rd!

## To Tear Down
```
$ docker-compose down --volumes
```
