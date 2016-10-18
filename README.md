# erd-docker
Dockerfile and docker-compose.yml to utilize erd (https://github.com/BurntSushi/erd)

# Usage

```shell
$ git clone https://github.com/rkawajiri/erd-docker.git
$ cd erd-docker
$ docker-compose run --rm erd -i sample.er -o sample.pdf
```

If you want to use in other project, just copy docker-compose.yml.

# Build && Check on Local

```shell
$ cd erd-docker
$ docker-compose -f docker-compose.dev.yml build
$ docker-compose -f docker-compose.dev.yml run --rm erd -i sample.er -o sample.pdf
```
