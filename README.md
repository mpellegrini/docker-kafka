# docker-kafka
A Complete Kafka environment for development and testing purposes.

### Build and run with Docker Compose
```
docker-compose up -d
```

### Once running you will have:
* Apache Kafka (localhost:29092)
* Apache Zookeeper (localhost:2181)
* Confluent REST Proxy (http://localhost:8082/)
* Confluent KSQLDB Server available at http://localhost:8088/
* Kafka Topics UI (http://localhost:8085/)
* Kafka Schema Registry UI (http://localhost:8001/)
* Kafka Manager UI (http://localhost:9000/)
* Kafdrop UI (http://localhost:9001/)

### Stop the containers once you’ve finished:
```
docker-compose stop
```

### To stop and remove the containers entirely:
```
docker-compose down --volumes
```
Pass `--volumes` to also remove any associated data volumes
