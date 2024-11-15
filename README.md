- `.env` settings
```env
COMPOSE_PROJECT_NAME=radarr
TIMEZONE=America/Toronto

DOCKER_NETWORK=# name of docker network
IP_ADDRESS=# ip address of container

ROOT_PATH=# path to media dir inside container

# Update
MEDIA=# path to media dir
DOWNLOADS=# path to download dir for qbittorrent

SSL=# path for ssl dir
NGINX=# path for nginx config dir

RADARR_CONFIG=# path to radarr config dir
QBITTORRENT_CONFIG=# path to qbittorrent config dir
```