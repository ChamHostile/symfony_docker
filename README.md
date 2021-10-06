# SYMFONY Docker Project

## Technical informations

 1. Services :

 - Php-Apache 
 -  Composer
 - Phpmyadmin
 - Mysql

## Requirements
- Docker

## Installation Steps

 
1. Clone repository
 2. Launch docker-compose.yml
2. This will launch php Dockerfile
3. Launch bash from php container
4. Create project with symfony
5. At the root of project, modify .env and add `mysql://root:@db_docker_symfony:3306/symfony?serverVersion=5.7`to the DATABASE_URL variable
6. You can now use symfony with docker !

### Dev and prod environments
Modify `APP_ENV`variable in .env file at the root of the project.
Change "dev" or "preprod" value in the variable.
