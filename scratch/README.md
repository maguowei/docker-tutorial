# 定制自己的基础镜像

- [dockerhub scratch](https://hub.docker.com/_/scratch)
- [dockerhub alpine](https://hub.docker.com/_/alpine)
  - [Dockerfile](https://github.com/alpinelinux/docker-alpine/tree/fc965e3222f368bea8e07c1c1da70b6928281a76/x86_64)

```bash
GOOS=linux GOARCH=amd64 go build -o hello main.go
```
