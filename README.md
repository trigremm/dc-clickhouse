# dc-clickhouse

`cp .env.clickhouse.sample .env.clickhouse`

`docker-compose up -d --build --force-recreate --remove-orphans`

`docker-compose ps`

`docker-compose stop`

`docker-compose exec clickhouse-client sh`

`clickhouse-client --host clickhouse-server --user myUser --password myPassword`
