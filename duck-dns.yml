sudo docker run -d \
  --name=duckdns \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=America/New_York \
  -e SUBDOMAINS=<YOUR SUBDOMAIN> \
  -e TOKEN=<YOUR TOKEN> \
  -v <PATH ON LOCAL SERVER>:/config \
  --restart unless-stopped \
  lscr.io/linuxserver/duckdns