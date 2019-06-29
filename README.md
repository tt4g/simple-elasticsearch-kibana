# Overview

Elasticsearch and Kibana with Docker.

## URL

Elasticsearch: http://127.0.0.1:9200 (if from container: http://simple-elasticsearch:9200)

Kibana: http://127.0.0.1:5601 (if from container: http://simple-kibana:5601)

## Command list

### Up

Launch Elasticsearch and Kibana.

````bash
docker-compose up -d
````

Only build container.

````bash
docker-compose build
````

### Down

Stop and remove docker container and networks.

````bash
docker-compose down --volumes
````

Down and remove all images.

````bash
docker-compose down --rmi all --volumes
````

### List

List images.

````bash
docker-compose images
````

List containers.

````bash
docker-compose ps
````

### Delete

````bash
docker-compose rm
````
