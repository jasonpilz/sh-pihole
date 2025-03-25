# Pi-Hole

* https://github.com/pi-hole/docker-pi-hole/
* https://docs.pi-hole.net/
* https://docs.pi-hole.net/docker/

* https://docs.pi-hole.net/docker/configuration/

### Usage

```sh
nslookup pi.hole
```

```sh
cd sh-pihole && docker compose up -d
```

### Find Password

```sh
docker logs pihole | grep random password
```
