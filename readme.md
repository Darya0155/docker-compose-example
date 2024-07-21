## create Docker network
```bash
docker network create -d bridge arya-docker-network
```

## create mysql container
```bash
docker-compose -f mysql/mysql-docker-compose.yml up
```

## create mysql container
```bash
docker-compose -f kafka/kafka-docker-compose.yml up
```