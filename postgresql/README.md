# PostgreSQLのDockerImage作成


## Settings

```
$ cp .env.example .env
```



## Start up

```
$ docker-compose up -d
```



## Access To Server

```
$ psql -h localhost -p 5432 -U root testdb
```
