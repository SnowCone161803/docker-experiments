# docker examples

`docker compose build --no-cache`

`docker-experiments_large` has two RUN commands: create 1GB file, delete it
`docker-experiments_modified` has three RUN commands: create 1GB file, append to it, delete it
`docker-experiments_small` has one RUN commands: create 1GB file, append to it, delete it


```
$ docker images -a
REPOSITORY                 TAG       IMAGE ID       CREATED          SIZE
docker-examples_modified   latest    e26b75d1ea08   12 seconds ago   2.05GB
docker-experiments_large   latest    b644f03d9115   17 seconds ago   1.03GB
docker-experiments_small   latest    7ef34508bbcc   22 seconds ago   5.54MB
```
