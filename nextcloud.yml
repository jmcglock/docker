sudo docker run -d \
  --name=nextcloud \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=America/New_York \
  -p 443:443 \
  -v <PATH ON SERVER>config:/config \
  -v <PATH ON SERVER>data:/data \
  --restart always \
  lscr.io/linuxserver/nextcloud