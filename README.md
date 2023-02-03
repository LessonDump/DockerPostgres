# Postgresql на базе docker-compose

## Требования:

- docker
- docker-compose

## Команды:

- поднять контейнер: `$ docker-compose --compatibility up -d`
- остановить запущенный контейнер: `$ docker-compose --compatibility stop`
- запустить остановленный контейнер: `$ docker-compose --compatibility start`
- остановить и удалить контейнер и сеть: `$ docker-compose --compatibility down`
- удалить директорию 'pgdata': `$ sudo rm -R pgdata`

## Переменные окружения:

- `POSTGRES_DB` по умолчанию — **postgres**
- `POSTGRES_USER` по умолчанию — **postgres**
- `POSTGRES_PASSWORD` по умолчанию — **changeme**

## Коннект к Postgres:

- **URL:** `localhost:5432`
- **Username:** `postgres`
- **Password:** `changeme`
