# Linux shell in Docker

The Dockerfile builds an Ubuntu environment. Start an interactive shell and follow comandos.txt to practice inspecting files and processes inside the container.

## Run locally

```sh
docker build -t linux-shell .
docker run --rm -it linux-shell bash
```
