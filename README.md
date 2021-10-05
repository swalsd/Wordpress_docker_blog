# Wordpress_docker_blog
Using Docker to setup a Wordpress website environment.

## Components of the project 
- 🔴 A container for the wordpress cooking blog - with Wordpress and PHP
- 🔴 A container for the MySQL database
- 🔴 A container with phpMyAdmin to visualize the database  

## How to install and run the project
- ➡️ Git clone https://github.com/swalsd/Wordpress_docker_blog.git
- ➡️ Cd Wordpress_docker_blog.git
- ➡️ Git checkout master
- ➡️ Docker-compose up
### To access the website
- 🧑‍🍳 http://localhost:8080/
### To access phpMyAdmin
- 🖼️ http://localhost:8081/

## Docker images used
- 📄 mysql: 5.7
- 📄 wordpress: wordpress:5.8.1-apache
- 📄 phpmyadmin: latest

## Authors
- 👨 Adrien Le Dû
- 👩 Johanah Lekeu
