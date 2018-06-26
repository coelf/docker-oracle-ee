# docker-oracle-ee
docker compose for oracle entreprise edition database

## create docker volume for db data
`docker volume create oracle-ee-data`

## build image and create container with docker-compose
`docker-compose up -d`

## start container with docker compose
`docker-compose start`

## stop container with docker compose
`docker-compose stop`


## db info
|                |             |
|----------------|-------------|
|hostname:       |localhost    |
|port:           |1521         |
|sid:            |xe           |
|service name:   |xe           |
|username:       |system       |
|password:       |oracle       |

### To connect using sqlplus:
`sqlplus system/oracle@//localhost:1521/xe`

