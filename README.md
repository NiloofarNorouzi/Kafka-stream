# Kafka-stream
This is a simple Kafka application, including setting up a Kafka cluster locally, aproducer and a consumer as different services presented by docker images

## Setup the local Kafka Cluster
To run your Kafka cluster simply run the *docker-compose.yml* file in *DockerFiles* directory
```
cd DockerFiles
docker-compose up -d
```
- To make sure that both *kafka* and *zookeeper* are run successfully, check it via
```
docker ps
```