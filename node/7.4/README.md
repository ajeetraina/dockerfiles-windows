# Node

A Windows Server Core Docker container image with Node.js 7.4.0 installed.

## Building

```
docker build -t node .
docker tag node:latest node:7.4.0
```

## Onbuild

```
docker build -t node:onbuild onbuild
```
