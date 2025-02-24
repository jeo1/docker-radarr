- `.env` settings
```env
COMPOSE_PROJECT_NAME=radarr
TIMEZONE=America/Toronto

ROOT_PATH=/media #path to media dir inside container

# Update
MEDIA=<path to media dir>
DOWNLOADS=<path to download dir for qbittorrent>

SSL=<path for ssl dir>
NGINX=<path for nginx config dir>

RADARR_CONFIG=<path to radarr config dir>
QBITTORRENT_CONFIG=<path to qbittorrent config dir>

EXTERNAL_RADARR_PORT=<external port for radarr>
EXTERNAL_QBITTORRENT_PORT=<external port for qbittorrent>
```