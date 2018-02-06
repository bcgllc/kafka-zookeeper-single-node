# kafka-zookeeper-single-node
This repo contains a docker-compose.yml file for running Apache Kafka and Apache Zookeeper running on a single node. This is meant to be used for experimental and developmental use-cases. Do NOT run this in production.

This uses containers provided by [confluentinc](https://hub.docker.com/u/confluentinc/).

Note: Tested on Docker for Mac.

## Getting Started
From a terminal window in the same directory as the `docker-compose.yml` file, run:
```
docker-compose up -d
```
