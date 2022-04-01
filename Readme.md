## Blockchain Development Environement

```shell
docker-compose --file docker/development.yml --project-name onchain run blockchain npm install
docker-compose --file docker/development.yml --project-name onchain run frontend npm install

docker-compose --file docker/development.yml --project-name onchain up
```
