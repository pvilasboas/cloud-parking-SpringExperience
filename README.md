<p>Projeto desenvolvido durante o BootCamp Spring Experience - Dio.me</p>
<p>Repo do projeto original: https://github.com/sandrogiacom/cloud-parking</p>

# cloud-parking

## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=123 -d postgres:10-alpine

## Stop database
docker stop parking-db

## Start database
docker start parking-db
