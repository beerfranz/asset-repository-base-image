# Build Caddy with the Mercure and Vulcain modules
# Temporary fix for https://github.com/dunglas/mercure/issues/770
FROM caddy:2.7-builder-alpine

RUN xcaddy build v2.6.4 \
	--with github.com/dunglas/mercure/caddy \
	--with github.com/dunglas/vulcain/caddy \
  	--with github.com/greenpau/caddy-security
