# Docker commands

## Set env variables by command line

docker build -t app . 

docker run -e prefix=app1 app

docker run -e prefix=app2 app


## Set env variables by docker-compose
docker-compose config

docker-compose up