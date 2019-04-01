# docker-redis
Docker Redis

## Quick Start

- Start docker container: `docker-compose up` or `docker-compose up -d`
- Refer to docker compose document in [here](https://docs.docker.com/compose/overview/#compose-documentation).

## Configuration

- To disable all data persistence in Redis run this command `redis-server --save "" --appendonly no`. (default is added)