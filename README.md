# docker-compose-database

## list of docker compose database

- Mysql
- Postgresql

## how to use
1. go to folder mysql open in your terminal 
```sh
cp .env-sample .env
```
fill the environnment
```sh
MYSQL_DATABASE= #database name
MYSQL_USER= #mysql user
MYSQL_PASSWORD= #mysql password
MYSQL_ROOT_PASSWORD= #mysql root password
MYSQL_PORT= #mysql port
```
```sh
docker-compose -f docker-mysql.yml up --build
```
2. go to folder postgresql open in your terminal 
```sh
cp .env-sample .env
```
fill the environnment
```sh
POSTGRES_DB= #postgres db name
POSTGRES_USER= #postgres username
POSTGRES_PASSWORD= #postgres password
POSTGRES_ROOT_PASSWORD= #postgres root password
POSTGRES_PORT= #postgres port
```
```sh
docker-compose -f docker-postgres.yml up --build
```
