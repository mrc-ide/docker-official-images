# Docker Official Images

We are moving away from Docker Hub to GitHub Container Registry because of rate limiting issues.

There may be certain images however, that are officially available on Docker Hub so this is a small script to port those images to GHCR. You can add more images [here](./port-images-to-ghcr).

You can then pull them using:
```bash
docker pull ghcr.io/mrc-ide/docker-official-images/<image-name>:<tag>
```
