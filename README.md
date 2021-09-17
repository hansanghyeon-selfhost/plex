## docker

**main - swarm**

```sh
docker stack deploy -c <(docker-compose config) plex
```

**local**

```sh
docker-compose -f docker-compose.dev.yaml up -d
```


## Plug-ins

- [DaumMovie](https://github.com/axfree/DaumMovie.bundle)
