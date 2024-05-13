# Standalone instance of XAMPP with docker.

## Installation
- ```clone this repo```
- ```insert to db folder the .sql files to init dbs```
- ```insert to http filder the website files```
- ```run docker-compose up -d```

```
    enter to Apache instance and install mysqli with this command:
```
- ```docker-php-ext-install mysqli && docker-php-ext-enable mysqli && apachectl restart```
- Connect to db from mysqli use the docker network ip

## Uninstall
- ```dump all database and generate .sql files```
- ```run docker-compose down (To remove all keeping files and data)```
 
