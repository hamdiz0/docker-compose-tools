#### Run:
```sh
DOCKER_GID=$(getent group docker | awk -F ":" '{print $3}') docker compose up -d --build
```