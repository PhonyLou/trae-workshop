# Trae Workshop 项目

## 项目简介
这是一个基于Spring Boot的示例项目，展示了如何使用Docker和Gradle构建和部署Java应用。

## 功能特性
- 提供简单的REST API端点
- 使用Docker容器化部署
- 支持多阶段构建优化镜像大小

## 快速开始
1. 构建并运行
```bash
docker compose up --build
```
2. 访问API
```
http://localhost:8080/hello
```

## API端点
- `GET /hello` - 返回欢迎信息

## 技术栈
- Java 17
- Spring Boot
- Gradle
- Docker

## 许可证
MIT License