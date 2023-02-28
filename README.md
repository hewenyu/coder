---
name: Develop in Docker with custom image builds
description: Build images and run workspaces on the Docker host with no image registry required
tags: [local, docker]
icon: /icon/docker.png
---

# docker-image-builds

使用自定义镜像

目前支持 java 17 , golang 19 ,rust

## Getting started

First

```console
git clone https://github.com/hewenyu/coder.git && cd coder
coder template create
```

## Update the template:


Update the template:

```console
coder template push coder
```

Optional: Update workspaces to the latest template version

```console
coder ls
coder update [workspace name]
```

