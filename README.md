# bclec

## Creating docker networks
For deployment, `dev-net` docker network is needed.

``` shell
docker network create --subnet=172.30.100.0/24 dev-net
docker-compose -p bclec -f docker-compose.yaml up -d
```

