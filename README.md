# GameIO deploy

## Setup

```bash
# clonar repositorios
git clone https://gitlab.com/cymetria-2024/game-io-back.git
git clone git@gitlab.com:cymetria-2024/game-io-front.git

# instalar paquetes de node/npm
docker compose run --rm api yarn install
```

## Run with docker compose

```bash
docker compose pull

docker compose run --rm api npm install
docker compose run --rm app-build npm install

docker compose up -d
```
