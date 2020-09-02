# Jperezviloria | mysql-docker-configuration

## Introduction
Is a guide to create a MySQL container with Docker, I want connect this container with a Spring Boot

## Installation
To get started simply run:
`https://github.com/Protobot-dev/mysql-docker-configuration.git`

after to create the docker image we will need to run a container with next command:

`docker exec -it nombre_de_contenerdor_mysql mysql -u root -p`

when we`re on the mysql console, we will write: 

`mysql>  create user "nombre_de_usuario" identified by "contrasenia_contenedor_mysql";`

and later...

`mysql> GRANT ALL PRIVILEGES ON *.* TO 'nombre_de_usuario'@'%';`

**When this process was completed we need to take a spring boot project with JPA and Mysql dependencies**

***

## Connecting with Spring Boot



