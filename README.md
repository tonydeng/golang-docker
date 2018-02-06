# Golang Alpine Docker

[![Docker Stars](https://img.shields.io/docker/stars/wolfdeng/golang.svg)](https://hub.docker.com/r/wolfdeng/golang/)
[![Docker Pulls](https://img.shields.io/docker/pulls/wolfdeng/golang.svg)](https://hub.docker.com/r/wolfdeng/golang/)
[![Image Size](https://img.shields.io/imagelayers/image-size/wolfdeng/golang/latest.svg)](https://imagelayers.io/?images=wolfdeng/golang:latest)
[![Image Layers](https://img.shields.io/imagelayers/layers/wolfdeng/golang/latest.svg)](https://imagelayers.io/?images=wolfdeng/golang:latest)

基于Alpine系统的Golang镜像。

## 使用说明

### 获取镜像
```bash
docker pull wolfdeng/golang
```

### 启动容器
```bash
docker run --name golang -it -d wolfdeng/golang
```

### 使用容器内的命令
```bash
➜  ~ docker exec -ti golang go version
go version go1.9.3 darwin/amd64
```
