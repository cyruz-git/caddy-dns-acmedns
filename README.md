# caddy-docker-custom
Caddy Web Server with a series of additional modules (see **Modules**).

[![Docker Build and Publish](https://github.com/cyruz-git/caddy-docker-custom/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/cyruz-git/caddy-docker-custom/actions/workflows/docker-publish.yml)

**Docker Pull Command**

* from GitHub Container Registry: 

```
docker pull ghcr.io/cyruz-git/caddy-docker-custom:latest
```

**Caddy Docs**

* [Caddy Docker](https://hub.docker.com/_/caddy)
* [Caddy Server](https://caddyserver.com/docs/)

**Modules**

* [http.handlers.webdav](https://github.com/mholt/caddy-webdav)
* [http.ip_sources.cloudflare](https://github.com/WeidiDeng/caddy-cloudflare-ip)
* [dns.providers.cloudflare](https://github.com/caddy-dns/cloudflare)
* [security](https://github.com/greenpau/caddy-security)
* [http.handlers.crowdsec](https://github.com/hslatman/caddy-crowdsec-bouncer)
* [http.matchers.fail2ban](https://github.com/Javex/caddy-fail2ban)
* [http.matchers.maxmind_geolocation](https://github.com/porech/caddy-maxmind-geolocation)
