## Run

docker-compose up -d

## Delete

docker rmi $(docker images -a -q)
