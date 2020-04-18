# Docker Compose Sample

A collection of docker-compose sample to how install the applications into environment development.

## Get Started

Applications docker compose:

- [MySQL 8](https://github.com/danielcsrs/docker-guide/tree/master/mysql8/single)
- [MongoDB 4.2](https://github.com/danielcsrs/docker-guide/tree/master/mongodb4/single)
- [Postgres 12](https://github.com/danielcsrs/docker-guide/tree/master/postgres12/single)
- [Kafka](https://github.com/danielcsrs/docker-guide/tree/master/kafka/single)
- [RabbitMQ](https://github.com/danielcsrs/docker-guide/tree/master/rabbitmq/single)
- [RabbitMQ Cluster](https://github.com/danielcsrs/docker-guide/tree/master/rabbitmq/cluster)

```shell
git clone https://github.com/danielcsrs/docker-guide
cd docker-guide
```

## How to use:

Run **docker-compose up** or **docker-compose up -d** (on background) into directory of application. 

Example with MySQL 8:

```shell
cd mysql8/single && docker-compose up -d
```

