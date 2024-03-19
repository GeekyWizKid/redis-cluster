# redis-cluster

## 简介

`redis-cluster`是一个使用Docker和Shell脚本创建和管理Redis集群的项目。它旨在提供一个简单、快速的方式来搭建Redis集群环境，适用于开发和测试环境。

## 特性

- 使用Docker容器化技术快速部署Redis节点。
- 提供Shell脚本`create_cluster.sh`来自动化集群的创建过程。
- 支持灵活的集群配置和管理。

## 快速开始

### 前提条件

- 安装Docker
- 安装Docker Compose

### 安装和运行

1. 克隆仓库到本地：

```bash
git clone https://github.com/GeekyWizKid/redis-cluster.git
cd redis-cluster
```

2. 使用`docker-compose`启动Redis节点：

```bash
docker-compose up -d
```

3. 运行`create_cluster.sh`脚本创建Redis集群：

```bash
./create_cluster.sh
```

## 使用说明

 这是一个快速搭建Redis集群的项目，适用于开发和测试环境。您可以根据自己的需求修改`docker-compose.yml`文件中的配置，以适应不同的场景。

## 贡献指南

欢迎通过GitHub的Issues或Pull Requests来贡献您的代码或提出建议。请确保您的代码符合项目的编码规范。

## 许可证

本项目在MIT许可证下授权。
