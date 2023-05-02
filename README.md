# wordpress-docker

Use Docker to setup Wordpress, MySQL & PHPMyAdmin

## Warning this has never been tested and should not be used in production. This code is for educational purposes only.

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



## Wordpress and MySQL data

Wordpress and MySQL database will be saved in the folders wp-content and db-data directories. 

Backup your wordpress site by making a copy of these directories to a backup device or service.

To restart your wordpress installation back to the initial state just delete these folders.

## To Tear Down
```
$ docker-compose down --volumes
```
