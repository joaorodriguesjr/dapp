## Development environment

```bash
docker-compose --file docker/development.yml --project-name dapp run blockchain npm install
docker-compose --file docker/development.yml --project-name dapp run backend npm install
docker-compose --file docker/development.yml --project-name dapp run frontend npm install

docker-compose --file docker/development.yml --project-name dapp up
```
