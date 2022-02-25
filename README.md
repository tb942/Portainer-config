# Portainer-config
This has the basic portainer setup for my [nginx-served](https://github.com/tb942/nginx-https-reverse-proxy) portainer instance. I access it through nginx at portainer.lan (DNS'ed by pihole).

## Starting/updating
```bash
docker-compose pull
docker-compose up --detach
```