# Wordpress_docker_blog
Using Docker to setup a Wordpress website environment.

## Components of the project 
- ๐ด A container for the wordpress cooking blog - with Wordpress and PHP
- ๐ด A container for the MySQL database
- ๐ด A container with phpMyAdmin to visualize the database  

## How to install and run the project
- โก๏ธ Git clone https://github.com/swalsd/Wordpress_docker_blog.git
- โก๏ธ Cd Wordpress_docker_blog.git
- โก๏ธ Git checkout master
- โก๏ธ Docker-compose up
### To access the website
- ๐งโ๐ณ http://localhost:8080/
### To access phpMyAdmin
- ๐ผ๏ธ http://localhost:8081/

## Docker images used
- ๐ mysql: 5.7
- ๐ wordpress: wordpress:5.8.1-apache
- ๐ phpmyadmin: latest

## Authors
- ๐จ Adrien Le Dรป
- ๐ฉ Johanah Lekeu
