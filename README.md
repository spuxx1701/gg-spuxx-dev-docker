# gg-spuxx-dev-docker

A repository containing various docker configuration files for my game server host.

## Setup

Clone this repository:

```bash
cd ~
git clone https://github.com/spuxx1701/gg-spuxx-dev-docker.git docker
```

Setup `npm` network

```bash
docker network create npm
```

Start `npm` and `portainer` containers:

```bash
cd ~/docker/npm
docker compose up -d
```

```bash
cd ~/docker/portainer
docker compose up -d
```
