# 7 Web Servers

This an example configure nginx, that will cache only images.

## Start the stack with docker compose

```bash
$ docker-compose up
```

Example of requests:

![Example of requests](./example.png?raw=true "Example of requests")

Clear cache by proxy_cache_bypass directive:

![Example of requests](./clear-by-bypass.png?raw=true "Example of requests")

Clear cache by perl script:

![Example of requests](./clear-by-script.png?raw=true "Example of requests")
