# tailscale-compose

## Getting started

This example consists of a web app connected to a redis db which uses Tailscale as a sidecar container to expose the web app.

```cli
docker compose up --build
```

At the end of the tailscale logs, you will find the Tailscale IP address.

You can reach the web app by visiting http://{TAILSCALE_IP_ADDR}:5000

## Clean up

```cli
docker compose stop
docker compose down
```
