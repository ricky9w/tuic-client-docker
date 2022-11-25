# tuic-client-docker
Run TUIC client in docker

TUIC: https://github.com/EAimTY/tuic

Docker Hub: https://hub.docker.com/r/ricky9w/tuic-client

Docker Compose:
```yaml
version: '3'

services:
  tuic-server:
    image: ricky9w/tuic-client:{{ tag }}
    network_mode: {{ network mode }}
    volumes:
      - /path/to/you/config.json:/etc/config.json
```
