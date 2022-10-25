# caddy-cloudflare-docker

Dockerfile will build the Cloudflare plugin into the Caddy image. Add hosts you want to reverse proxy to into the Caddyfile following the examples. Add other Docker containers to the network if you want to only expose servers through the reverse proxy.

See "Create token" under #2 of [this site](https://samjmck.com/en/blog/using-caddy-with-cloudflare/#) to get your Cloudflare API token.

When you're ready, do a `docker-compose up -d`
