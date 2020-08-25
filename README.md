# express-api

This repo contains a trivial express API for purposes of demonstrating the use of Concourse to perform the following:

- run tests
- build a docker image
- publish a docker image

## Start Concourse

Concourse can be started with docker-compose using the relevant make target:

```
make start-concourse
```

Just as easily, you can stop Concourse with the following:

```
make stop-concourse
```
