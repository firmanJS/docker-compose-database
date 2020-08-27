# docker-compose-database

## list of docker compose database

- Mysql
- Postgresql

## how to use
1. Mysql go to folder mysql open in your terminal 
```sh
cp .env-sample /mysql .env
```
```sh
docker-compose -f docker-compose-mysql.yml up --build
```
2. Postgresql go to folder mysql open in your terminal 
```sh
cp .env-sample /postgres .env
```
```sh
docker-compose -f docker-compose-postgres.yml up --build
```
