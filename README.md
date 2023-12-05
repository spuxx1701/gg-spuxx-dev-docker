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

## Set up a docker runtime user

We'll set up a user that'll have limited privileges and that'll be used by the game servers.

```bash
sudo adduser --uid 1337 servers
```
