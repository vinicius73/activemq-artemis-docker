# ActiveMQ - Artemis Docker

This projects automates the docker build generation of [ActiveMQ Artemis](https://github.com/apache/activemq-artemis/).


## Building

### Requeriments

- [Docker >= v20](https://docs.docker.com/engine/install/)
- [semver-cli](https://github.com/davidrjonas/semver-cli)
  - `go install github.com/davidrjonas/semver-cli@latest`
- [Task v3](https://taskfile.dev/)

## Commands

```sh
task clone
task prepare

task build:all
task push:all
```

## Docker Compose

Check [`docker-compose.yml`](./docker-compose.yml) to see a example of usage.