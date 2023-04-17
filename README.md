# docker-compose-database

## list of docker compose database
- [x] Mysql
- [x] Postgresql
- [x] Mongodb
- [x] Redis
- [x] Sqlite
- [x] Elastic
- [x] Rabbitmq

## how to use
1. go to folder mysql open in your terminal 
```sh
cp .env-sample .env
```
edit `.env` file and fill the environnment
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
edit `.env` file and fill the environnment
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
3. go to folder mongodb open in your terminal 
```sh
docker-compose -f mongo.yml up --build
```
