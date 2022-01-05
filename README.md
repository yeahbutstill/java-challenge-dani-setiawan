# java-challenge-dani-setiawan

* Setup Postgre in Docker

```shell
docker run --rm \
--name regis-db \
-e POSTGRES_DB=regisdb \
-e POSTGRES_USER=regis \
-e POSTGRES_PASSWORD=PNSJkxXvVNDAhePMuExTBuRR \
-e PGDATA=/var/lib/postgresql/data/pgdata \
-v "$PWD/regisdb-data:/var/lib/postgresql/data" \
-p 5432:5432 \
postgres:13
```

* Login psql

```shell
  psql -h 127.0.0.1 -U regis regisdb
```
