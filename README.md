# Docker Apishell Image

This repository provides a Docker image for the `apishell` project built on top of Monkshu. You can use it to run the API shell server in a container.

---

## 🚀 Pull the Image

To pull the image from GitHub Container Registry (GHCR):

```bash
docker pull ghcr.io/ananya-deeplogictech/docker_apishell:latest
```

## ▶️ Run the Container

To run the container, use the following command:
```bash
docker run -d \
  -p <YOUR-IP>:<YOUR-PORT>:3000 \
  --name apishell \
  ghcr.io/ananya-deeplogictech/docker_apishell:latest
```
open http://<YOUR-IP>:<YOUR-PORT>/apps/apishell/do in your browser to access the API shell.
