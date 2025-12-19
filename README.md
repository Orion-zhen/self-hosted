# Self Hosted

我的自托管容器模板库, 用于家庭服务器.

## 快速开始

本模板库适用于 `dockge` 管理面板.

```shell
git clone https://github.com/Orion-zhen/self-hosted.git /opt/stack
```

接着进入 `/opt/stack` 目录内, 搜索所有 `<changeme>` 字符串, 并做出对应更改.

端口号设置:

- `50xx`: 用于部署容器管理服务, 比如 `dockge` 管理面板, `beszel` 监控面板等.
- `51xx`: 用于部署服务型容器.
