# ActiveMQ - Artemis Docker

This projects automates the docker build generation of [ActiveMQ Artemis](https://github.com/apache/activemq-artemis/).


## Building

### Requeriments

- [Docker >= v20](https://docs.docker.com/engine/install/)
- [Task v3](https://taskfile.dev/)

## Commands

```sh
task clone
task prepare

task build:all
task push:all
```