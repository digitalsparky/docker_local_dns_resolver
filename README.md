Local DNS Resolve server in Docker

Also available on docker hub (https://hub.docker.com/r/digitalsparky/local_dns_resolver/)

Run locally using:

docker run --restart=always -d -p 53:53/udp -p 53:53/tcp digitalsparky/local_dns_resolver
