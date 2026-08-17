# Docker: Mealie

## Directories

```bash
/mealie
    .env
    docker-compose.yaml
    /mealie-data
    /postgres-data
```

## Setup

In the root directory (where `.env` and `docker-compose.yaml` are located), run:

`docker compose up -d`

You should be able to access the site at the `BASE_URL` you noted and the exposed port.
I can't remember if it defaults with https or http.
