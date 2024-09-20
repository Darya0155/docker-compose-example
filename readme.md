## create Docker network
```bash
docker network create -d bridge arya-docker-network
```

## create mysql container
```bash
docker-compose -f mysql/mysql-docker-compose.yml up
```

## create sonar container


```bash
docker-compose -f sonarqube/sonar-docker-compose.yml up
```


## docker-compose root app

```bash
docker-compose -f hostingerSetup/hostinger-docker-compose.yml up
```