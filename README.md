# docker examples

`docker compose build --no-cache`

`docker-experiments_large` has two RUN commands, one creating a 1GB file, and one deleting it
`docker-experiments_small` has one RUN commands that creates a 1GB file then deletes it


```
$ docker images -a
REPOSITORY                 TAG       IMAGE ID       CREATED          SIZE
docker-experiments_large   latest    b644f03d9115   17 seconds ago   1.03GB
docker-experiments_small   latest    7ef34508bbcc   22 seconds ago   5.54MB
```
