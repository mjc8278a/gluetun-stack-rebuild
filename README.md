# Gluetun Media Automation Stack (Rebuild)

Ports:
- qBittorrent: 8080
- Jackett: 9117
- Sonarr: 8989
- Radarr: 7878
- Torrent: 6881/tcp, 6881/udp

## Usage
cd /volume1/docker/apps/gluetun-stack-rebuild
# Fill in .env with your NordVPN *service* credentials
sudo docker compose up -d
