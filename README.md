# kafka-dev

## Setup Host for Kafka Access Outside Docker

```sh
sudo nano /etc/hosts
```

```
127.0.0.1   kafka kafka.local
```

## Setup Network for Kafka Access Inside Docker

```sh
docker network create kafka
```

## Run

```sh
docker compose up -d
```

## Server Access

```
kafka:9092
```